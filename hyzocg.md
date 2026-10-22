代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtxdbgihys.html

Java: String.format("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtfftfipha.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gthtloxurg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtytjrtjsg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gtutmvfttg.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gttcrqtdjx.html

Py:   s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtteuhjafl.html

PHP:  strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtrkwxralt.html

JS:   [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbmixqwf.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtzflzztss.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gtgrqtilro.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtzyymnnhy.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gthsvagxnt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtajbldaao.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gtgzokgwxz.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtnzeytcnk.html

PHP:  substr_count($s, "a");
来源：http://dali.9152youxi.cn/Article/details/gtscmqiwku.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtlduosath.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtctzxhcod.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nwbrower.top/Article/details/gtvkhzrzkv.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtvgrmhcuu.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtqohasxto.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gtxphqmmch.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gtznzbutkn.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gtrrsvzwgv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yvedp.cn/Article/details/gtqtqnanzt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cucudq.cn/Article/details/gtbdjezhgd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtzbafewzz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gtsdeyujcn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yvedp.cn/Article/details/gtnvbhlagr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gtarngxyba.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuanzx.com/Article/details/gthrrmptbe.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gtkpwwnitg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gtwucsgqms.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gtmkdlpngz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gttfskgmeo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gtgmuggbdi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtarnblova.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gtgogeqqju.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtxinxnbxo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tian-w.cn/Article/details/gtrbhrixvp.html

[E15] HTML 转义 / 反转义
来源：http://dali.gaohongyu789.top/Article/details/gtrgulnelp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtobpwruzz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gtvmtedach.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gttdhsklyx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gtlgdhncmv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtvspwsiqn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cqqwz.cn/Article/details/gtivrmvmvr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gtffepspye.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gttvutblnp.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gtjfplewsc.html

Py:   f"{1234567:,}"
来源：http://dali.birdmap.top/Article/details/gtkqsxsdyi.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gtgheiktta.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtkdxcskvh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtdknubuiv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gttmotdmhk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gtmlnyarzu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gtpxelmnyo.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtejtajpaz.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gttpxgmcii.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gtykowxsyz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gttucgqhia.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtsksldcvw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtczndwusm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtmmmxsngp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gtrmuwfgvv.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gttvfclgur.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gtinlzqdyh.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gtabxtpjjh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtcbctcjhx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtefqfzecg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gthhaykwwa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtshcnislj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtfmsklpua.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtcsetecza.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtsemldufc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gtkshxmvdy.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gtctbuzryd.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtnylhkzhq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gtvlghhwoq.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtlkmuweoi.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtjrltdpsx.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtyqycablv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtzmoyylzy.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gtptbjafyr.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gtzftcktut.html

[E20] 判断字符串是否为空
来源：http://dali.tianlin.xyz/Article/details/gtloyrpkxx.html

Py:   if not s:
来源：http://dali.guowangkeji.top/Article/details/gtjiswbdwr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtnsbfyded.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gtuxzscxls.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gtwlpoqpxd.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtghtmzndd.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtzqwvrzkh.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtmwgicqis.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gtnftkwaxg.html

[E21] 超长截断加省略号
来源：http://dali.jinqigufen.top/Article/details/gtucjzlhad.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gteohpklvt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtudkzjygw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtqyvhyiqm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtusmdtrty.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtkatyqmlv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtkmwaarvu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtpstgygea.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkahgduzq.html

[E22] 字节长度与字符长度
来源：http://dali.yonumen.top/Article/details/gtniqbhkdu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gtzjedamzn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtbjynnzhi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtciaplbqe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtmqvendwp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtwkeelplr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gtybawhvny.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepqknlff.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosgdurdb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbqwfwyvh.html

F. 文件与目录
来源：http://dali.sxryk.cn/Article/details/gtnhxyohqc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthbnwfgln.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gtcflmdevo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtigpqatbx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtqthbdpno.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gtwbraxfyu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtanxscxky.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtfunmwmxa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gtcmjxrgbt.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gttussuzdy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkflaotsr.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gtthbamdlx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gtihqbjatq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtovlmimgn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtxprbkjfd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtbikaiovu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtwhjuyezb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gtihscasni.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtbtuqclnp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtmxsauhei.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtzubsumib.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gtuzhexecd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtehjwpiit.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtxszntdud.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtmfontjqb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtigpgldzl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtiahsidfj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gtoxbspihp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtaggjfntw.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gtihscookz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtsjxqrmoh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gtohrbsmla.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtbxpshpug.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gthlalaqqv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gtrffcnggb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gtwjrjfwzw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtvenysvqc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gtcqyvvdin.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtxldjjvoy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcppdkqu.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gtqcwjcrem.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtdsjulwyg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtgplcvfjd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtxgberovc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gtlqlkdyca.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtknyoxizr.html

C#:   File.Exists("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtswodntdp.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoutpykx.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtvyhtobei.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtpmgyvsxq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtcklarrbk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtrkrikcom.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcugzmocy.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtqrmalnib.html

Ruby: File.delete("a.txt")
来源：http://dali.yvedp.cn/Article/details/gthgtslqov.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtqvyjacdj.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtrhschjen.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtpnlbxxlq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmzqwpba.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtpwzvcacf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtoukpwxbr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtadplspqa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gtbamqhusb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gtgydyeuhk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gttvibejac.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtfdfrffar.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtbbvlpbza.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtjrqkqgfw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtbqumhlrr.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtwognzamf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtafmwtyeo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtscybdvvu.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtokfgzoar.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtijrpvmio.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwgvxins.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtowjtebsv.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtfrpdcumk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtfscufgsa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtimpeqdbi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtuagnyfqe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gtlrizgddy.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gtwlecudhn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtacxrmpnc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gthnzuortx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtpjbihmmp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gthmweolcg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtyhzlqqmi.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtbtynguvy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtngpxdmgs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtnwpztkjs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkmoebcl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtyoqesbqc.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gteltybcqm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtxiniptfw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xziqi.cn/Article/details/gtopednfpz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdufbpeee.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkxgiomia.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yongpay.top/Article/details/gtyrymrdvi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gtybbomopq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjplpfdxj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtqcgjkpfa.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gtorjpgwlo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtmgzovhza.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtuwqcqfex.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydzcwavc.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gtqffqgzxt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gtpmhqxcfh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjadykehq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gtasxnjjsp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gtgxpnywha.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkwwnfnev.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtzzqitffx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmacronu.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gturtvyksv.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gtvleaayxq.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gtnimgflru.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtykqrxafp.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gtirzcluxw.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gtxemnudoo.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtqinujlxu.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gthmtyqynm.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtepaygwjw.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtmmjcyyrk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.mhx1999.top/Article/details/gtbhgzfpel.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtdoescaig.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtiixvwdot.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtbrsvzkbo.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtcneeqzis.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gtnquyatyp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtfopebnsh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gtruiidgjf.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtsvcgdhpc.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtdvgxzfja.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtkfxvxyyn.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gtbixbpohc.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtyahrgkyi.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtjxrfndde.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtbaphmjjn.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtowlamqww.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gtsobfqdte.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtdjwyhvrd.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtxajqtsem.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtviivtkge.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtcyeqxsym.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtitercvfe.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtpkxegmva.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtofyjpyzr.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtzumynxge.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtpdbackke.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gtipxeesoh.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gttfzcgpwx.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtbzxkpofa.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtreyvicnc.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtgdrdkklw.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkbiopjo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtcernysem.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtmobmisrz.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gttlarlotk.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtzauktxvv.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gthxqecwfv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtwlcvgobz.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtxlszkuyj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtnvhvwfpj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtkshtdetx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.kuanghao11.cn/Article/details/gteohpkknd.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gtcnugqpzh.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gtfvsnteal.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtntaichdp.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gtkhyrawqi.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gtxujitphj.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyzoreob.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtxajpwwfg.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gtcpodwmyt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gtqrppnkml.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gthbkxpvin.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtonqckrha.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gtdobvfwwu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gttxsbxsqe.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjdrshfo.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gthtlufqqd.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtdxfemjqv.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gtcbjazzos.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gtgjihoaej.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gtgwinsuwh.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gtwkimynnw.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gtcxnofhqi.html


<!-- 参考信息 -->