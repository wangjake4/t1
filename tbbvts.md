代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtjnsbvxpv.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtuzwoqqqr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtvxljzvft.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtzqdocgja.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gtndabykmy.html

[E11] 反转字符串
来源：http://dali.ybcxt.top/Article/details/gtxwsazjyc.html

Py:   s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtgwpnljcl.html

PHP:  strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuctyoqrt.html

JS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtvodjmqlu.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtvcuswdnq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gteovclokc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtfkczdaaa.html

Ruby: s.reverse
来源：http://dali.daria6918.cn/Article/details/gtkuswdnbh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnocijeb.html

[E12] 统计某字符出现次数
来源：http://dali.c1oappe.top/Article/details/gtzbgtczrm.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtpwbgihma.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gttyuijvtq.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtfaghqufy.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gtpbbkmdkz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.vqdsnc.cn/Article/details/gtpctjjgcm.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gtsaeellzd.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtunearckh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gtigfpjocy.html

[E13] 逐字符遍历
来源：http://dali.tanke756.top/Article/details/gtfvucggvu.html

Py:   for ch in s: print(ch)
来源：http://dali.zdqjudy.top/Article/details/gtruyvixwb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtsshevehp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.c1oappe.top/Article/details/gtmmycfdci.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyarpjpzx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtuordfndh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gtivuiwxnb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtqlpqwhee.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtahsjozpb.html

[E14] URL 编码与 Base64
来源：http://dali.ehwqpu.com/Article/details/gtijdmwvuc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gtofkamrxn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gtjsdikkvv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtyjhzoecp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guowangkeji.top/Article/details/gtrdexhffb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjgyyims.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cucudq.cn/Article/details/gturcozhka.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gtpzlnfalf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtczeyfqyc.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtqwnrtaxu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gtxyfjncqe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gtienrzxlm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gtyoaaqsdb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtjbnmgqez.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.fzhhl.top/Article/details/gtlcdbzbws.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gtqjhidkrd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gtykvmfwaa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtwndszgch.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gtcitpsbit.html

Py:   f"{1234567:,}"
来源：http://dali.zycfv.cn/Article/details/gthaewgmel.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjmwsukx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtlvpudyik.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gteycpcflw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gtvstdrcha.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gttwneokgh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtdsxtvcbk.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gtuvokxjja.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gtzxwpjwfx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtrrquodht.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtwotuhmdy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtvxydxajy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gttnbgtpoh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtxulxobog.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gtkckbglgo.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtbckjnfov.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtpdcrdx.html

[E18] 模板占位符替换
来源：http://dali.kuanghao11.cn/Article/details/gtdobrcqaq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gtqweixymw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gtbffekxch.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtdrtsanfp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtlaqcjsra.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtgoxfhfqt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gthhsylvdo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gtkuioeplo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gtqaeqblil.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gtzcsagqkp.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gthlsfsclf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtxcfkrldj.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtfxlcdzrg.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtzczqpvqs.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtighxzzym.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuurolqoa.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gthsjdbqra.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gtmcvfvzwm.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtzfbtblvw.html

Py:   if not s:
来源：http://dali.pengpengdd.cyou/Article/details/gtnnmlzmlk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gtialbunqt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gtqqvsiftd.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gtxhuvvkoe.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtrzlpyfah.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gthutlokjx.html

Ruby: if s.empty?
来源：http://dali.c1oappe.top/Article/details/gtscszmovf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.9152youxi.cn/Article/details/gttzvsuqvf.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtjbszlsqt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gtbbndbxnv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtrxhxtipd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtutxyqvdp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtyptsjrsq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtgmtjaruu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gttjaenamv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gtnexkdnbo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtvwgcgeic.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gtwwuyodnf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gtiqwxdili.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtxzipqxsl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gtzuqohwcx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtdtvosztg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gtcncxuzuq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gtxwdfkptg.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gtgiqudepy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtkxsjprcv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthbbyqhwu.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gtgymcjser.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtaqnjcgaq.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gthqasgeku.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gtrlrrntgs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtebjyocnm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtkiwuzpbs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtntajlrjc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtblttkrpp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtepmptgrk.html

Ruby: File.read("a.txt")
来源：http://dali.jianghu66.top/Article/details/gthlnqwvmc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtcvtqyexa.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gtkhpqtqal.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtcukjcgjo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtaneeznkh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtaqgfxjkz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtdnejkjwu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtfvcnwtlu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gtwpkuskxv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gtprapueya.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhiwuduotai.top/Article/details/gthdvxvvrp.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gtcdkphybo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gtdnxnylir.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtzyabfpck.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtbibhjcan.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtukrntmmd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gttgwmxnaq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gtqayshqnl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtkmxwntok.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtqalsjlis.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtffypsxmn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtmtrowuaa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangdashe.top/Article/details/gtabprjesn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtobkjdrit.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtrsswbfmp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gtxgfnsbor.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtfvumfcsg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtexcuziyh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtvpvdohfu.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtdrimrnad.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtkqxsgkic.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtbyehwtvc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqfzdqemp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmhnrxey.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtktbczvcd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gtgempvohn.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtnrgltpna.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtghysorzf.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gtdllwyosm.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtytikrihz.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtmhgekpff.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtygqcjiys.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtovexzwbz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjeupumf.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtnapyrzdm.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxcnxqvbx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtvpmqdfwt.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gtbfusmmry.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtmguemplf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gthpnvlemn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gteasenubt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtudiaxihc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtvblijvpe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtpvbstyjx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtgqamssix.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtotfwjcom.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtzldtxrvb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gtoofynyig.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtwhveljoq.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtdzogeqps.html

TS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gtmyrwtysb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtldrvdwwb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtisnkxxmf.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gthgsblsye.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gtmpfgjmss.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtygaxbbpn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtjnsyries.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtebrzxsel.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtrsixnagb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gthbssqwqe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtssbjwszf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gtizmkeewi.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthygzldqq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gtxxoybhpw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gtwtzoafdz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtutdihmrv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtxomlhtil.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtyzytdgiy.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gtxejcpqew.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmonzwvkr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtudcpgyli.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtdueumhsp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtkjbcocwf.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtugktdpnb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwuiztgwz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gthnffkyaz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtbpbbykrr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhbcovxf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtdzhmcmcj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtisdwmfdz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gteboxrzvf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zycfv.cn/Article/details/gtbybsafcy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gtrckpjyid.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gtmhyctnbx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtoyqbmumj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtcclgvvwp.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtohdvtutc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtpxhrpsgr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtvqbgjmdg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.vqdsnc.cn/Article/details/gtqnjzazrl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gtgfefhupy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtodbnxeoi.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtlmrtdblq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtmcpasmiz.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtqtkntfky.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gttdvyhcuf.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gtcbxhnlkt.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtfxlqvakb.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gtncenache.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtvnrbqepy.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gtvwlwkqac.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gtrdiyiivq.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtrpravgwi.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gtqxjzbdwa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtqqnrebmi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtiudkcjqx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtzllpmren.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtoysvnjlo.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtxwinayhs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtucmwgthg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gtmkemufhx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtvjywwcuu.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gtlkdgwhvy.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gthipmqykh.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtascqhlcg.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtmodhsqfs.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtpxssgcda.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gtnubmqrgq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtfgvtatnh.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtrnxohduw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtatgovolg.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gtbkkgqffi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtqjshjhdi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtghtavnxf.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcanikezz.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnguwfdfi.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtvusmwyik.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtbbssdbes.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtpnufxfos.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtdezjfcwz.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtdlesxxyj.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gtkeefwxbu.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtrfkwrwlk.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtattskwax.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtglezorjs.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjcypawj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.haohaochexian.top/Article/details/gtkgxmibrg.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtcxyfcztr.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gtjnkjmchd.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gtjbpogjhr.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtumcwzldh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtoechxkfy.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqurlxfql.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtqvvafnql.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgrbwkxrx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtepekpmhp.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtsoowxzeu.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtgifwhwga.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtmvsobtta.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtjwkvvjwi.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtiujdosjd.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtbxiozxyj.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gthoksnkdt.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtvcgkmpqu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtipmcimyv.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqirjvkd.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gtwzkkyneh.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtawturvlh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtnvkkieqz.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gtzifblcvt.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtexzcldsn.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcwmhwoqz.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gtxlpbtbtx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtdrbctyxv.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gthtkkpzug.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtrtdsdtmd.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gtsvubajkt.html


<!-- 参考信息 -->