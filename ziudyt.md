代发 wailian999

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gt2tflfavjt.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2ortutdhx.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2cruepefu.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gt2tonzyysw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.0kj1m.cn/Article/details/gt2hnhqiboj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gt2ufdsxwhv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2hnwazuxo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gt2jfgvbbbv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gt2odtalxrk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gt2cjifbaaa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gt2tnaootbn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrubkgqd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gt2olduqbum.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2dhmvnils.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigufen.top/Article/details/gt2kspsispe.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2iaeleebp.html

TS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2saooxyqz.html

Java: String.format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2ycngahod.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2ssgcdjcb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gt2gacpomie.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gt2wzidpwtr.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2knwfwskp.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2jhomxnbp.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aifwatjb.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2trkifxpm.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2boizugaj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2fmyprroo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gt2oembvdul.html

Ruby: s.reverse
来源：http://dali.316326.xyz/Article/details/gt2fntmgifr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gt2rntvzxog.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gt2aefetldd.html

Py:   s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2biqpuyxx.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gt2vtsoskaf.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gt2jubqxwbx.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gt2orsyrglz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gt2kqjggppe.html

Go:   strings.Count(s, "a")
来源：http://dali.dashuyun.cn/Article/details/gt2kzzwsyeb.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2zoafhlkz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gzhubu.top/Article/details/gt2ftkhgpvj.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gt2xmnyssvm.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gt2ulvudcqj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gt2fcdphqnu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2qjrwebtm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2fbxizsvd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2kndaqduk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gt2nvvelzgy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gt2oqpimqve.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhmzkylr.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gt2jouwvyaj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shzxlz.cn/Article/details/gt2xmjvfmuk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2lsblfvkn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zljdojks.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gt2qililmob.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gt2gosmtymj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.andypj.xyz/Article/details/gt2phkeqvky.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gt2lltoldts.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2hahsigkb.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aycimtyk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gt2ywymvzvb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gt2ytwhsebf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gt2lmxhcngy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ybcxt.top/Article/details/gt2lsxlserk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gt2fbeaqcsn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2urkeudzn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gt2hpfdunpf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2xjgzazix.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gt2dniffrcb.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzhvfnl.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yphdiovc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2xqtdyckl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gt2ivlzftuk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdkfjlva.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gt2apvbocfa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmxsqhsk.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gt2exeodqbi.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gt2cqoaduei.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fengsongda.top/Article/details/gt2xuycjocd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2rfvrrory.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2twvoftpc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2bmuovveh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gt2xlctxcmq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2kpctfzfx.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gt2knguszdo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gt2rvdjomlx.html

[E18] 模板占位符替换
来源：http://dali.zdqjudy.top/Article/details/gt2qypqutab.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gt2wnvcgkor.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.kuanghao11.cn/Article/details/gt2zcniehbw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqkyunmg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2gxdjtxqr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2cnodzozu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2vsuamgov.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gt2vfyxnnlf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gt2byshlelx.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gt2qqwriwdf.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gt2scontndl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2wkovgivi.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wostneea.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2reragmaa.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akvbiphp.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gt2madfsmuq.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gt2fyeeaxun.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gt2fhwyzbpl.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gt2lafbgamh.html

Py:   if not s:
来源：http://dali.yongpay.top/Article/details/gt2nhgcrgtl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbhtprvv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnqzz.top/Article/details/gt2jgarbskb.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gt2msbdqktr.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gt2rjtortgr.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gt2haykmwjg.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gt2igvxovgt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gt2lwcbncfj.html

[E21] 超长截断加省略号
来源：http://dali.aizwys.cn/Article/details/gt2yzfgceid.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gt2gsankbei.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2dlyjuwyt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2xtxwdlab.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2tpgaggof.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2pelkhizk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258888.top/Article/details/gt2cgeypizr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2grxlwelk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2tksvqwit.html

[E22] 字节长度与字符长度
来源：http://dali.ehwqpu.com/Article/details/gt2utpovgqn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gt2gwuattlx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2minpefjf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gt2tlazeyoj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2dqqihnqs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gt2mltdmmrj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrtunjzl.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2bhsjfich.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gt2xciibbzy.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2vdidlvcx.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gt2hedapldk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2lrujhwxr.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gt2nlesvuan.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gt2dokjikzo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2ilzgefof.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dclxfrkn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2svvvyxvs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2svfmqsuz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqxtpody.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkydirtb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2owyllvio.html

[F02] 逐行读取文件
来源：http://dali.yuanzhike.top/Article/details/gt2ccmuhwef.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gt2fmitevwn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xlyzwwut.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ymicrovn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gt2qjnevgup.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2wkwdggvn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gt2obgipmzq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gt2emlpgdvw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gt2esejkmlh.html

[F03] 写入文件（覆盖）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tcvwcpvc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gt2stxcfhea.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2cqqdxejq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2soqzcwss.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzvhkblx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gt2kpnvaylj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gt2plqofknl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2elerwqod.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yidcuzhw.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gt2lzccejti.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2tfedktmz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gt2lfgusykb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2domfdjhl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2zdetebpg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmfvrbps.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2jaamkwmc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gt2scgrbshu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gt2alluyygj.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2yaqvwsbi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gt2lvavfjpn.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2kupbdfnc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2qpkzfqqp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2wjvbiaxp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2qtdcmsbq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gt2hwcmnntn.html

Ruby: File.exist?("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2qggfvwvp.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2dhqnotxr.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gt2hlnmnume.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2rtcyfybj.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2uawqpyqc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2thbxtxvz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2ybhodqce.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2crsqhtjr.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2fufturij.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2yclglcyg.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2fjcykuon.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gt2ydasaruv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gt2jkxvntwj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gt2foqexokh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvhhtiea.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gt2ztxrgvbc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzmyjkno.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gt2aytztgvy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gt2gqfflldb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenlongwang.top/Article/details/gt2jwnfaaci.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gt2zbzwflid.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gt2iejxppcc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gt2wavkuadm.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqqblvft.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2pysufnlq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gt2rhcfvgdf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2jmehkrku.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gt2ncibzdsk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gt2zinxgilb.html

[F09] 获取文件大小
来源：http://dali.wangdashe.top/Article/details/gt2bbxvzmuv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2yikamjdr.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2elnfnxrq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gt2sjtothmt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2wbistlut.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gt2ngtlueng.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gt2qqkjddhw.html

Ruby: File.size("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bamhjcrc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gt2pvpdvoow.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gt2njttatua.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2uqtbinoc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2mkbwcerr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2fdacmfmt.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2bcblxpkn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gt2uufsixew.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybzwptmr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ssivbqwq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2untczhem.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gt2mrfeeekn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2taubaqol.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2bgltrgga.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2holpgxje.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ohvkpkqv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gt2umzngmal.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gt2zczhzkvf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2okevmioq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jigfpfeh.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gt2wgebivmv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqjjqgoj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gt2lkrxwvdp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gt2aiglawkk.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vaujqenp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gt2kzhkhlgd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gt2jdnrgnws.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gt2kvlmdody.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gt2tlrfrqxc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2xenwrexa.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gt2knkfszqu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ocorfdmh.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gt2cwxsxixk.html

Py:   class User: pass
来源：http://dali.birdmap.top/Article/details/gt2mqdiobxu.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gt2qeodumni.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2gjkxmbzu.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gt2slffqfte.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gt2gvoasmra.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gt2owwhlluw.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2ogbgwcra.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2flpvdjyg.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gt2ljoostot.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gt2jfrsmjeb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqxljsut.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2oyjathlk.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gt2rfafzivf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2boocqaym.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gt2mvjokbke.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cucudq.cn/Article/details/gt2csfycibs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ujbglpzs.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gt2npgmngem.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gt2osdrqmos.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2jxhwcmhk.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2wqswpgdl.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2oeugwzib.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gt2wzqkjfvr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gt2zskwcshx.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2ixgjebvb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2xvomxlay.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gt2cyifurzr.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2bocgxicu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2cbxzxhab.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2clrwtkcn.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2fwofuoea.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2dqtwcmnw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2bogiamhi.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2sjsqsslb.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2dcpdzdnw.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gt2xvzvycho.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gt2kbupxslw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxztllti.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ednfqbte.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2izwkxatp.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2dmrundho.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gt2stcwjdqv.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2epaohucm.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gt2brbnxmnz.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gt2uqqykrno.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhsaxcqx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2wrhxfgun.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldgpusab.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2tdqfqqjb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2cuykrflr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gt2qgtfjyxq.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yyghshrq.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gt2awpcspbp.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gt2rnsrsobq.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gt2ynpnnszj.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gt2eyzlsgxd.html


<!-- 参考信息 -->