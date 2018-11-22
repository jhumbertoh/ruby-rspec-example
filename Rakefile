def run_tests(platform, browser, version, junit_dir)
  system("platform=\"#{platform}\" browserName=\"#{browser}\" version=\"#{version}\" JUNIT_DIR=\"#{junit_dir}\" rspec spec")
end

task :os_x_10_13_6_chrome_latest do
  run_tests('OS X 10.13.6', 'chrome', 'latest', 'junit_reports/os_x_10_13_6_chrome_latest')
end

task :os_x_10_13_6_firefox_latest do
  run_tests('OS X 10.13.6', 'firefox', 'latest', 'junit_reports/os_x_10_13_6_firefox_latest')
end