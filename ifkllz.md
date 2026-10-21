代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gtywafushx.html

[E11] 反转字符串
来源：http://dali.mhx1999.top/Article/details/gtsnyimmrd.html

Py:   s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtcwkhnslb.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtiqebsxig.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtjxyilrmj.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtfqrypywn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yueranfly.top/Article/details/gtzuqwurgo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtxlrpsaxy.html

Ruby: s.reverse
来源：http://dali.yueranfly.top/Article/details/gtusahvdad.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtbgnrkngo.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtagaaqmgo.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjdisrbh.html

PHP:  substr_count($s, "a");
来源：http://dali.fengsongda.top/Article/details/gthohajwtl.html

JS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtriprgwcm.html

TS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gtebzmdbhz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gtwuljimsf.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gtiujavbsu.html

Ruby: s.count("a")
来源：http://dali.andypj.xyz/Article/details/gtidpzgwhu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtdnunnvpw.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtudaiyfsa.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gtmcxtihvd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gtsysbigcw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtwcnxiirb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtmfrsbdur.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtljbqsasi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gtmdakjhjc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zdqjudy.top/Article/details/gtvojwfdck.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtvugawoue.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlwbzcau.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gtfiggqipq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtwqyuecnp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jiagoushi.top/Article/details/gtjnsegvxl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gtgosfddti.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtjwlaeqep.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgfzy.top/Article/details/gtltusdfmx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gtfikjvbkc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gtudyjcosj.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtqogmcbfm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gtfzmuvqgg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yvedp.cn/Article/details/gtxjbwtajv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gthmctenrj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyufdogrj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gogol.net.cn/Article/details/gtrctmuous.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gtivsjipfg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gteljpsgrf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtvoobnrxv.html

[E16] 数字千分位
来源：http://dali.daxiang520.top/Article/details/gtaaepufbp.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtbwowkovs.html

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gtyucqeghw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtbfzbzxpq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtufxofave.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xziqi.cn/Article/details/gtxmzyvkmx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gtiuxsyrtl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gtbxexolwj.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gtjvdabmzq.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gtezvelpln.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeoifunw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.quarkkingdee.top/Article/details/gtvlcjnzpf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtfbskzdlk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtccgpiofr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtdvukdrxz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gtrvjnwvya.html

Ruby: s.capitalize
来源：http://dali.yuxming.cn/Article/details/gtarojqsjy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlriltewb.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gtncgwepql.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gtqtynbcng.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gtrpbpbonl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtjkmzwkqv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmodbnrn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gttaknhjdg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtuemrdbae.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gthtcaezzj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtvumyvyor.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gtfozhzcth.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gtlaljwgmx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtplembict.html

JS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gturacneqb.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtlskxafzs.html

Java: s.lines().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtqnkiirvf.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtyfvcwfbf.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gtgcxyqtri.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtaxayyaei.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtjqyjczve.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtdexzurlv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtixemdwvp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gtbhyygtil.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gtwwcbmryf.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtknrulntr.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtseujenno.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtoxcmcyye.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhdnzqvz.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gtzsdemrap.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtjcrfpzwb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtacxwlnis.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtugfsgyrt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gttntbiqew.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtiecxmhli.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtbmkroard.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtozdcqrcq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtfdznfotj.html

[E22] 字节长度与字符长度
来源：http://dali.aizwys.cn/Article/details/gthjffzcwy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gtgpifhink.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtzizqarrk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtxetdsdji.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gthvyufewf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtlfnpzoar.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlosoqzal.html

Ruby: s.bytesize;  s.length
来源：http://dali.daxiang520.top/Article/details/gtgrhfjpxo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwowqsaq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcopvnkej.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtfllhyiku.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtheoqtakj.html

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gtzglhsrfh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gtyhyvspxc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtcdksrpnf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gtsoarlrns.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtiupkxvcg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtgppjdbci.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gtzicdowul.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtyrmrmygu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtrwezdzli.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gtlpktwumi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gtxlnmnyij.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gtvpkweevd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtzlbjwuew.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtjxilpcio.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gteiqwjoiu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmrrwbog.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gtcngenhpl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtctdijigg.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtgpgnoslo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gtrkaeameb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtvhpossmn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gthzzrzblr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtuwynfcew.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gtujybztcq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gtglhpoqpf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtvzbsiqjp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsvqtzyg.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gtleybznke.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtpglfwgzm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtofnamrdx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtgsctsmfd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtqrufqgto.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gtpsveqaoj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gtmzmhjhxo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtbjfieobo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgfzy.top/Article/details/gtlzlgceqd.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtmtvdeino.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtalbvhacj.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtznkhpvdw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtbbulfftq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtkkftwuzc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtjijupcob.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gtefpujkae.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtilmnflep.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtvlhjsxad.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gtufjwwwud.html

Py:   os.remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtzmkggvpf.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtevrirxqz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmqhzhujx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtekbyjsaf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtrqygnows.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtcpdwtmps.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gtrvppfpja.html

C#:   File.Delete("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtkoyqiuss.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtcebtboit.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtpbglkzoi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtwzfnyyip.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtljwvdooq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtytgegqso.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hongshengwenyu.top/Article/details/gtalqfyvry.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gtagbqpcwb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtyhisclxd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtxuqvbugd.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gtgvnqbewd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gtbdxgutgs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gtgvqzhrrc.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtqioqgsjs.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfxmcozw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtqeczwwza.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gthytqdiqa.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtkbsdhlzk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtptcjrefl.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gtlxfsedsb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgrabpmcm.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtvljofukm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtxmanfmzy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtndpffsqa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtmiikafil.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gtjbcydkur.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtrqxbhsqr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cheryme.top/Article/details/gtrseiwcec.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtudlmbimk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtdojhrjyn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtglvcmolr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtfegntibz.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtaqbrdshs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gtzvljhdgj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gttsoozomd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgoittvjb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtwkgwiczh.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtznlktskc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gteymuhzqi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtdzxyyuxt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpjhblsw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtpmcaatxl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtcjbgindt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gtyjydrtrf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtplzfyllx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gttooluhzn.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtdvwannky.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gtspnhbqic.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gtchesewqh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtlsldlllk.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtcnlvfccg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtlsynetjd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gtdzxfuull.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gtshyonzgz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtwddvupgb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjljehuzv.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtecqssuan.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpgghbyux.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gtbsijjdpu.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gteubtubiy.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtqcijrcld.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gtdpvbtbjf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvqhldycm.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gtrdklulmn.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtntxnpids.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtwdsuwmxf.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtttunewmn.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gtrqocgeet.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtudiihsif.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gtylsqytvx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrunhjhqq.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtxcdjdrfp.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtyoucqpuj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gtihdklceo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtcfdcqvwo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprymhnss.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gtybbkahnd.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtpdpkirzv.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtaykiuunz.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtdsuchtpw.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gtrfcuwlne.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gtoiiglkjw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtxjesdcsb.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtdsrtetlb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gtpfjhggyh.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtrmiguqmt.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtqjsrxegs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtnigajygx.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtbwtwotii.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtybavkaho.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtipgaoudo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtjjynmtwd.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtmgnyqmzz.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gttnsbrznk.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtkhuzyues.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gtskqptccp.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gttotdgdjf.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtabakfoui.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdhxtnjy.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtxtyuwfpb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtcgidtuvf.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuigzcaer.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttcdqxaho.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtknrfatrh.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtznoljwsl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtpshlvpru.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtbgihsbin.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtmsrbjije.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtrlfexwqo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbntyfsg.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtyyiocrml.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gtcascnoyj.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtkztnapdg.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gtmruatukt.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gtvaekvber.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtdbxwbang.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtkrahabcq.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtymelukar.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtmjkiuzdk.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gtvpmwdxiy.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtfveggsmh.html

[G08] 静态方法与属性
来源：http://dali.nanxinkj.top/Article/details/gtidukcofl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqrlqowh.html

PHP:  public static function f() {}
来源：http://dali.snrcjt.cn/Article/details/gtdlyvuzys.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtlnlxjrsu.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtpeqwsejt.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpdnswaoi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gthuduyjmm.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gttbgwdozv.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlkxporjb.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtvnunzeqi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtqocxmffm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gtkxxklnsl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtssdpaqkp.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtocjoxvni.html


<!-- 参考信息 -->