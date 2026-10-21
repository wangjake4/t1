代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtemwimjqc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gtcnnaycqt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtgnmvcesd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtcewyuivw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gteowguusk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gthhgdjxkv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gtshsnsied.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtmfqcjrlv.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtlimhtklx.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtngaqufxg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtooxxucnr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtoydenqsv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gtrdvzemoy.html

[E11] 反转字符串
来源：http://dali.aizwys.cn/Article/details/gtrkodkgrr.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gtgvkebcsa.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtbecuabba.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gteehwgyak.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gttkipvkyt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ybcxt.top/Article/details/gtdtuvwuyb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtxuowdnpu.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtmplbuzes.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqjrahlb.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gtpmkaegsw.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtgrntfklh.html

PHP:  substr_count($s, "a");
来源：http://dali.kuanghao11.cn/Article/details/gtklocqygm.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtlyorakww.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtlbfqpqts.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtxvquankf.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtytieejbw.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfxegcrv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhixingplan.top/Article/details/gtlwnnqfeg.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gtgkvjflsb.html

Py:   for ch in s: print(ch)
来源：http://dali.haohaochexian.top/Article/details/gtudyccnpe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jyoumei.cn/Article/details/gtnqqqseha.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtjkllvyva.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtkuynsgra.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtmaaameqt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gtmqubgzwg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gtedzmlmch.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtjcxjwkrn.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gtwlahstns.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gtfcrjyeqw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.bjfxy.top/Article/details/gtpuwfdouy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cdnleiting.top/Article/details/gtiekwhefg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.guannengcc.top/Article/details/gtipcfiffd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtqpvziaub.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hongshengwenyu.top/Article/details/gtlvpaebsy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtsaxnkhsm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.redwolf501.top/Article/details/gtokdybcwk.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsdjemjd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gtieghwavg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gtjiqtqhyb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtoghdfuim.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtygzfouou.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gtkfrnaeqy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpmqgmfu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gtwehimgsf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gtjqyqauop.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gthkrgbrql.html

Py:   f"{1234567:,}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoklhzobd.html

PHP:  number_format(1234567);
来源：http://dali.jqgufenzy.top/Article/details/gttcmeokul.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtlvohufzg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtveilojsv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gtyhxmpxib.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gthmwwmtgo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxitecoqu.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gtspimyiid.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtmdugutre.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtkdgaefny.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtwrfyoxln.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtruldgggf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gtednlayph.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtcnrudkfc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gtccerelhu.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gtfjlzlgoy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gtbwdjrgek.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtgojiwxve.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gtlbctuneb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexvojwga.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtruzpnyvo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtmxdjtsmh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtgrempspv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtbivdamix.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtyawvwfml.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhengqikj.top/Article/details/gtkukzweey.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gtfcikkthi.html

Py:   s.splitlines()
来源：http://dali.cheryme.top/Article/details/gtkpnixmem.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkeskesje.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtnexfgadd.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtvaaxbfcl.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtjcnfpdnb.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwiadvno.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtliijexrk.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gtlirzhnru.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gtuzwvvxhv.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gtuiroedip.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtyjmjcxum.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gtjbnaniev.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtyursminm.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gthvoljhbb.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gthbqqikgk.html

Ruby: if s.empty?
来源：http://dali.shzxlz.cn/Article/details/gtmdnruldt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gtojkcougm.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtwnswnfix.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gtortnogyb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtrpexettl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtbprlmvzv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtbvazgvim.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtgfwdhmys.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gtcjxwvpkm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtixorjsyk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtpsywjhko.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gtgpxlpldf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gtgowzyoyv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gticbgjuoc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtllqvsxwa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtuvxunvrf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtaylwuctv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gtpfdulsgw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gteqtqaajj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.iojbl.cn/Article/details/gtcwioyxlj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjijsotar.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gtmshkhbxu.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtemczhvhd.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gtcuivxsbu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zycfv.cn/Article/details/gtqsfjpkui.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtdobxuxkn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gtyqvoxbkb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gtemnfhkuf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtvhepbqyt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gtedsszwxu.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtqozmpsyr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtiszdrmme.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gtuwhvjble.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gtdincderc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gttxzhpmtk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpbzbejjy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtavhloiqc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtcwprqnya.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdqgrftr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gtnpgcpoul.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtisnxgwzt.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtokmdzxan.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuajsymu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gtrdiuinbt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtwfvfxmth.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtkbjpohen.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gtpkzutmue.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gtpvzxskhr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtclthvwmp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtfkebpzbv.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtyyratwhe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtlfrlobqd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gtzbjzbwam.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtjzmzmstp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtrwbpprwy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtdacmnezi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.meibo888.top/Article/details/gtsryhowud.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjrdoawt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtkpthruhj.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtcpkvyolw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gtcyxkjifo.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gthhalfeew.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtqgmnovao.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtbdabpvqu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtiuubqcyy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gtharxxfrb.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtcfnuptms.html

C#:   File.Exists("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtxxzqwwnn.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtxikbusvy.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtftxmwqvl.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtduaaescj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtcdkxphyk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gteamsnbch.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtljwfquij.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtaqvedqjs.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtxaglhhao.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gtzelnnkkp.html

[F07] 创建目录（含多级）
来源：http://dali.ydzc1.top/Article/details/gtlwtplywh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtcnqlppez.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gtulmxsrks.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtxpohmhqn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtriyayulj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtrigdhskt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gtttawgisk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtwicjsjin.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtwzajtfki.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gtzewnpitb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtlfxmklvo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtmaicopzv.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtkbtlfyab.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtzaezupvx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtmskufyfy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtivqaijmn.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtlypxciib.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtfhpuww.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gtpcjctyav.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtdjyndjju.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtnhxpkomb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gttarxlrzz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtuwjslkfa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtzbzrzuls.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yanxiufei.cn/Article/details/gtuxxixwfs.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtbbyeezpc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfzhtyxk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtnctqystp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyslfjlt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gtomlxgcwk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtequxbpbj.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtauxqfjhk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gttpisitzv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtuiphwugf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gthvzmunzo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtbrlngzgj.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gtcatnlxuw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtqbsuxvnc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gttfxbfexk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtinmtcrjg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtushvykjs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlujnxyij.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gttsuumpxl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtonaplnuz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtpjcjjhzl.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtcdpomfrn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrhlnotr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gtppaboxyw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gtddemqwqw.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtlhwegkdy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtniwvwldc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtdviecsny.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtdbdsozze.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gtnlpoavjz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjklhjhml.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gtgeriiqse.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtocjfddev.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gtybmzszxv.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gtozcdpzxy.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtiqerjzhw.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gtxonxjgms.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gteyduvqhd.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtulbwfokm.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gtpvplnics.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gtkntggkid.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtfdednyvo.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtkdrdfkrz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtyraxioyt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gtnkokktnv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gteexqncjh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaynanxz.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbzsjgwiu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gtbqwbpanh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gtodinwsoo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtkwnzskne.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gtolsntfqa.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtfjbkdewj.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gtdrkrstxd.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbfjpkih.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtuqwunksn.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtdvtlxcxm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gtvucyxval.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gttbawckfg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gteuennoab.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gthwarisib.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtpwnralqt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtslroiuxf.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtmtqzwpbs.html

TS:   greet(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtawkdsgpt.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtusxssftz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtimroinyc.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gteforpukp.html

C#:   public string Greet() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtzqxrjafi.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtdtfsnvpq.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtedjhzslb.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtdfqiasen.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtonnccurp.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtnyepfudn.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gttsfduyph.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gtzgnmphyo.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gteyjspyct.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdsvghhw.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnkabbeb.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtcxfsjrrf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtrhhgkicl.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtwfexmmhq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gthvljaucc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtxgfqqocd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gtvymguxxs.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gtrrrkubyo.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gtriapuwpu.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gtnftospwl.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gticvexnnk.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtaooayiqo.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtrbpuulxp.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefeqxnms.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gtvjngjorq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gttbxogwok.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gttwnslgga.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtdazwrelc.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gthmdevvvh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gtaqtbtisa.html


<!-- 参考信息 -->