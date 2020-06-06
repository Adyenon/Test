# Test
for i in range(1, int(frame_num) + 1, 1):
    self.by_xpath("//table/tbody/tr[{}]/td[2]/input[1]".format(i)).send_keys(min_price)
    self.by_xpath("//table/tbody/tr[{}]/td[2]/input[2]".format(i)).send_keys(max_price)
问题不大，重在细心
