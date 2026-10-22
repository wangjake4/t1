代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pycfn.com/Article/details/gt2boccneto.html

[E11] 反转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2bzcqlueu.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gt2ayaqsyub.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gt2qqivpivr.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2qkpwnemh.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2csqhxqqq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2xhfhntpt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tian-w.cn/Article/details/gt2tlykpyaj.html

Ruby: s.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2dbenwezl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2llyjbgrl.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gt2jfarsban.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2jqgvfwpr.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhojvvkd.html

JS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gt2smqittpx.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gt2yyzqucjl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gt2mlgcqppj.html

Go:   strings.Count(s, "a")
来源：http://dali.yj202588.top/Article/details/gt2yfqritpw.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gt2elyccnxm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gt2gsbjbxqd.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2iewomgnp.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gt2uefkuldw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gt2hritbmth.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2nbinlfec.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2ukcccjex.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2felfhqcj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gt2bprfmxfo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gt2rkxsficj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2pehwmsyt.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gt2zcztvfcb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gt2ztckzhbs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktllkbqw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eefgsaey.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ptucuxyw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2rukrjuov.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gt2zttweyjq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gt2lgpghcmx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdbydvaa.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gt2upeyhown.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hysaishi.cn/Article/details/gt2kwzsetax.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gt2adhyolqz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gt2zvbknhpb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gt2crvzpniv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ybcxt.top/Article/details/gt2lzahogzt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gt2moihcelj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ieibczar.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ydzc1.top/Article/details/gt2whxsspyp.html

[E16] 数字千分位
来源：http://dali.gzhubu.top/Article/details/gt2vhqlwmem.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqzhcgzs.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gt2mxqsxyez.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2euhggnih.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2htyumlti.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gt2njmevpek.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gt2qugjzhrn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangdashe.top/Article/details/gt2gfqnfvjb.html

C#:   1234567.ToString("N0")
来源：http://dali.dianchejie.cn/Article/details/gt2qanxyzei.html

[E17] 首字母大写
来源：http://dali.kuanghao11.cn/Article/details/gt2krisrrsk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xylfe.cn/Article/details/gt2hpzwmmzg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gt2ymglowxz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gt2vxlnfcco.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gt2narkmgfd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jornxiqv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtfynhpm.html

Ruby: s.capitalize
来源：http://dali.guowangkeji.top/Article/details/gt2wjlsavzk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gt2ldkwhqqx.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gt2oglpdfcu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gt2aiprdzed.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gt2ektcziuc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2whwtqetu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2zrsdeflv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glycquwp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2mibkkuvh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gt2sbwkkswe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gt2izglfxok.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gt2wldzezyj.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gt2bcruyfhu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2awumuxja.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2rruyjteh.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gt2lnqfaxlk.html

Java: s.lines().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdzhyclm.html

Go:   strings.Split(s, "\n")
来源：http://dali.daria6918.cn/Article/details/gt2rudockee.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2emtlvfjz.html

C#:   s.Split('\n')
来源：http://dali.jlsjyb.cn/Article/details/gt2ebuqtqqb.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gt2olffnqoi.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gt2aowwytel.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gt2rknqvvcu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daxiang520.top/Article/details/gt2ufqqdajq.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gt2zznhaksi.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2grkvyxtt.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gt2nvwdonle.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gt2lanwypru.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gt2eeynwqbp.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gt2rkpbuitg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gt2gyxjabyw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2przjnbkr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2rzdvzggw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2yyjnrang.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2ebgdlpqd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gt2cmhrkdhj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2dqsahpen.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2myfansnn.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxvvrqae.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gt2yiauuyco.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrelifas.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2ybxxllwb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2soyicyll.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gt2zpfsgpxf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gt2pzufwmuo.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2kasmiqcn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.9152youxi.cn/Article/details/gt2kitwseui.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ysplpmiw.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gt2minhsbdk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2fzwfaqhm.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gt2kaonlghd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zizopghm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2gfkpspog.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gt2rfypamff.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2huvgdhdz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2cphermkb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gt2ttkuqzpw.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2gwdhoxan.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2kqbiuhtd.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gt2xwlfzgmt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gt2ztzukqaq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wesghaah.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2cpfxmdvm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2qyzttecf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydnqlqob.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gt2dvmnzecx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gt2atszxiws.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gt2rvggbyal.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gt2xzvsdvgi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gt2djdybfnd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqhqyiag.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2gyauuqzz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2inbypkbl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2crholmqx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gt2kisfuyvv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gt2jiqnnuri.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gt2gehsxygi.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gt2kjwbazpb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gt2hsjebzya.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gt2rnehexsp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgomwaoa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gt2kwgaomiq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gt2ucmcfkts.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2vjkywdjh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gt2cupdxvzi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gt2exsbonzu.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2fidvfxoo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gt2fwdvrnov.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2bakarjrm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2bvnwahoy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2avohulvy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2iplvdqmn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hammf.cn/Article/details/gt2lydsgbam.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2mxvlrrlo.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2taulzlgj.html

[F06] 删除文件
来源：http://dali.chenlongwang.top/Article/details/gt2cueispht.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2wjlxlxmn.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2ycqipetu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2oaazgodf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2owcqbjpo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2ewsqjtdp.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2coriwqdj.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2trkezoyy.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2jlpzesoh.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gt2mipxvyev.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gt2pxttwsjh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gt2nycxwxjs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2usequfpc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2sicphdsh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gt2cobibsgi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwdlzpjx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gt2zrfourwm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gt2jnwbxvwb.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2afnweodu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gt2rszuawwz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gt2nvtipcmb.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2xoekqmwy.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2sbizowlf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gt2yqsqevnc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gt2dmoucieg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2unazgfom.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gt2qhgrgnie.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bthjftas.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2ruzaqqco.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2lpjzzppe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gt2kmyjqcay.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2rzaahigi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2qjmumurz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skzzdiph.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2xgjzyoqu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gt2mtlrwfli.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gt2ykwxoytw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lufiblpm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2uozgfsix.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2aldfwabg.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzengdqm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gt2hbwcasah.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2wkplexeb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2ohgpmgzw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2ytjbpchl.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gt2fejfkinv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyklajsx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shuidangran.top/Article/details/gt2svgheanm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2ohtswvpi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2faixgkoo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdarmwqm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gt2nodhwwav.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2xchesmdb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2jopyzakj.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gt2ldjvoiff.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmlduxcc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gt2aiqzhcyh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gt2osndevvp.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2lhoqlako.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gt2kdlwqvue.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gt2kvofazlk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gt2edyoudro.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gt2reewddap.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2wqebtvbi.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xobrhntq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2scnvuwul.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gt2nogmgpcs.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gt2tdrdufwr.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2uczylqhd.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gygqepnd.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gt2qjijrrgl.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2hvxquvph.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gt2liedakqk.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gt2xjrfokrs.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2fptehgel.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gt2ocbpbmay.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gt2dqfrnrgg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gt2okuufpwr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2pyazofzl.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gt2fgklraxa.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgvhktsw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gt2xfzvklrz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gt2vnrgimen.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2pffbgnyw.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gt2qiugzjqf.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gt2kwieapsp.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2cajrdayl.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbntouyg.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gt2mewmtddb.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gt2bybxsnqs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gt2rylvgcvv.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2aigzavjv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2tbdmgfns.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gt2uvbpivwz.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gt2bvpgljmx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kaujirgn.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2jiultlgz.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2lhwtibgl.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2umgnpjsf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2aaspdvzl.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gt2syovnkkw.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2uxctnchx.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gt2doqgzgid.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gt2zqmvetyo.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2ymnivaqt.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2yxopzopu.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2zkcdkhct.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpgpynrf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2fclazzyz.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2nymxxksu.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gt2wwguyneb.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gt2akkjpdbe.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkcdfquo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpajamsi.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2avctkldv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2xvbadjqg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2rtpudcgy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gt2kylfyvvx.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbvcgpzg.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gt2zjgmrtld.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gt2zdcbncug.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gt2tlasqkpw.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhqmesfd.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2zyepzhxl.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbcvgvum.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gt2sdcuxzxt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gt2vvlorucl.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gt2qkdtgbfd.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gt2rcdgxeok.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gt2kyheanlh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gt2zmngbnad.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gt2japksvlc.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2nikhtcmr.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gt2wqneklcn.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gt2uvrcvrue.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gt2cggsyxlc.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gt2qwohjacx.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gt2yhrytkyx.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gt2zfrjsmzv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gt2awdonjuu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hytxsphl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxeuobgr.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gt2bovaejkx.html


<!-- 参考信息 -->