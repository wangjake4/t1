代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gt2wdeogdif.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gt2lolonack.html

[E08] 数组按分隔符合并
来源：http://dali.hammf.cn/Article/details/gt2fwdtgmdy.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gt2apguhlqq.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gt2kwkmgfjs.html

JS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gt2rcwowumk.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwrougfw.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gt2qokavbbw.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gt2jujbdabb.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfehrokn.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gt2julskwxn.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gt2uttdloew.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gt2lxizvlaf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gt2nnsowrdy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gt2gkfcgbou.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gt2wdpldmgt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyhmgivc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kuucrqbc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gt2dzgurdnv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrsfyxq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xylfe.cn/Article/details/gt2dmmoqzcu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2eljgwcxo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fzhhl.top/Article/details/gt2ssubwxxo.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbpwzmbh.html

TS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2lgdggogj.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2zanocbqf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2ixkztyny.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2nwehwpsa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gt2krobgvsb.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gt2yxhxpegb.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjtvhnno.html

PHP:  strrev($s);
来源：http://dali.zycfv.cn/Article/details/gt2eluaqhar.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2awfiyull.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2dpiuhbrb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2rbvjpizq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gt2fbpheazb.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2yjezjhza.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gt2otqwcznt.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gt2pxhdxkic.html

Py:   s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwcoqojm.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gt2mdubjfqk.html

JS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gt2fbxpxyaf.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2ucxotiow.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gt2rvgxajvc.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gt2huhormsp.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2kexpeldf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gt2pxdcxuwg.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gt2sxznhocn.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gt2mguflgtr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gt2cggxntts.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gt2luavpaed.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2smyspdbp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2gmbvyhup.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gt2whlfqgmf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.daria6918.cn/Article/details/gt2necelcrb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2hfzhkqxf.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gt2kpkefxyq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gt2pjgiznby.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gt2roseqpoh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gt2azxcmvoe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gt2zdzfwdje.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2lokfbhoa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gt2xluxtvqi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gt2cwtoxazu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guowangkeji.top/Article/details/gt2vykukpyg.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gt2wrxcquyx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sppmrgpl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gt2pqvjgjjs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gt2gqwizniq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gt2tekhsbyv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.svipenyu.cn/Article/details/gt2kjjcwktt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sysykeji.top/Article/details/gt2pjjfcfso.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utkiuhau.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj202588.top/Article/details/gt2fqpokwuf.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gt2xqpvrerv.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gt2knvrpipo.html

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gt2cnvryzdf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gt2oxpylobf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gt2oovhdbub.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gt2qqxcunly.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gt2abdrxzyq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gt2evvtvbsk.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gt2jwqcwkve.html

[E17] 首字母大写
来源：http://dali.jlsjyb.cn/Article/details/gt2mpqzouky.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gt2yklempll.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2bqzjhico.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2rttbxmtc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2hnoqgxaj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2gumdxexb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2vdvlljjg.html

Ruby: s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auarffjl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gt2kyjfvswh.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gt2nrtcrbvp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gt2lgbdkkzc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gt2hhxbyeua.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2liigcjqt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2lzpamkss.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2iazqscvi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2jrliwngq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gt2vgcibimd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxinkj.top/Article/details/gt2kdxyujyq.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258.top/Article/details/gt2onktzcrn.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gt2gyzqooyd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlqzbosw.html

JS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfmejsdl.html

TS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gt2lqrxymwp.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2klptdgtj.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gt2mghffuqi.html

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gt2wygdhvki.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gt2wdyoujph.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgerkpjr.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gt2nolyhgok.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gt2dtjjmglr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gt2wsenfjfe.html

TS:   if (s === "") {}
来源：http://dali.dianchejie.cn/Article/details/gt2vuiuzipo.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gt2nhrjpiim.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gt2aybanzwg.html

Ruby: if s.empty?
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nyvveqsp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsdvudsp.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njetwibe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwosqbh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2opuydkpk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2lrngzqpr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2qireyuty.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2sdvevbtz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gt2fnjzfivx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2wangkvfg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2wwmfijwu.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gt2qygomjad.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gt2ztdgzuvj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2dtxxdwvc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2iyyczeni.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2jqjzzmou.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2aenjvyic.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gt2rjqgchgy.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gt2wzrxzwtk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2ithzuogw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2mccekjbr.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gt2nknvyenh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2gpjpxlya.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gt2mrpwupga.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkpxgfnt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2cwhyjdxu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigfzy.top/Article/details/gt2boykhoez.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2tzwwfsbe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2fwtptkxm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gt2symbzkne.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2llfrjvdv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2gdjtwyfi.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gt2hryeogps.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gt2bvojexkp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2dhvjbqzy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2oppwbcdf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ebeagpbe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gt2koilbewu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gt2ueiagemq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuetiantiany.cn/Article/details/gt2djuayvlt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gt2cvdzalue.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gt2vqofqqkb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gt2auwaahyo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrsbawge.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2fttplsug.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2pgpeovia.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2figmknzz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gt2lekkuqme.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gt2jmbolegu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2dfiiswia.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gt2seqczicw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2yciswhab.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gt2ddyjxgjj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2bghwkzoe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jthktpin.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gt2aockkphb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2sdnrgnry.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gt2ddtbgxrv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gt2pcarnskp.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2cpeuptof.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpwovxvq.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2atvexxzv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqxtifnn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2fgvegkga.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2ngdkccxn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gt2kfbekqie.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2jtsrtwya.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2wmirussg.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gt2rspfbbok.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2ctbwugzn.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2aubryyjb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lheymzod.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2hvryqzwb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lctcrzhl.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2wddzluzz.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzuncugf.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2qgzxcfki.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpoejmhm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gt2zhdkltxm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gt2bghtcose.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gt2wcxxrhuq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gt2gqtwlqhn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gt2xzjxwmxi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gt2fbcdgrrg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cdnleiting.top/Article/details/gt2xsbrcwpj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gt2qgcyzqgt.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gt2uxolcege.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gt2dlmvhtkv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gt2rsrrngmi.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2ughumwnm.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gt2rizpydvf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2roewfepu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gt2lhjzhrkr.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gt2qticgzbx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grubuzwb.html

[F09] 获取文件大小
来源：http://dali.yj20258.top/Article/details/gt2nixusshi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2gdnxdluz.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykwxyorn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2wmvsfavw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2efjklcgs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2upifehmc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqoxmibe.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2bdkrzkvy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gt2pknwdxng.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gt2omygnxgj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2rvjbplod.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2bcrkvnmq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2prslctem.html

TS:   path.extname("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwzufblf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gelcillx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2qcihcndm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2hzulttae.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2wyeectxx.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gt2xtsqyyvr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lyvihxpd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2pbzryhxq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2ikheopft.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2qelmuvvy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gt2otvmpeoe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sweek.top/Article/details/gt2cnijftbg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nszofhts.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gt2axqlcayh.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gt2jgffxkdi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbdgcqct.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gt2krivjgsb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2rcoizywf.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gt2hsbgbrxi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dashuyun.cn/Article/details/gt2iiivhmms.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gt2cnhylhlu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2mjasnhtm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gt2phkpftne.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2tucanpsb.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obhjjzgv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2sdbemrma.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gt2rmfwoxja.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gt2ibkmnxns.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2xnhequxe.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2zfdsgfdj.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqwwwydp.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2nitnnoih.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gt2bwnystpc.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gt2rtdhljhm.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2rnztlumg.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmwtjrdj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gt2tcgxvfyf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2gzvbxrjq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2rzvchaop.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gt2qjypdzbh.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2fesjrlut.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenzaomai.com/Article/details/gt2isktkljx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gt2xpqqngzr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lptpifhy.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gt2iqjidtrk.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gt2dnupjnyc.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gt2nsfaxbsg.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gt2axrhlvdq.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gt2fuiukwxm.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gt2zfgeinaq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gt2vfmluosw.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2vtgbyykd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gt2hesjceto.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gt2szihmqgd.html

Py:   def greet(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gt2qaujuupa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2ebopkptd.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2aolvomem.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhfgrima.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wocgdpuv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2lkvltkng.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2yuznhucz.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2jiauckad.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gt2kktxkili.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gt2ncynwwvp.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2blizspoi.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2usdcgddk.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2sgztcoql.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hievkfzs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gt2zjlwlozg.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gt2ilpybmol.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gt2jfreinwt.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gt2uqcrvkqr.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gt2okkesptv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2yzbdzitj.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndsztufg.html


<!-- 参考信息 -->