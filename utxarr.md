代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.zdqjudy.top/Article/details/gt2gfvyklgj.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gt2kbudrtmm.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gt2blwsbgqb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gt2phhvjisi.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gt2cbacbfis.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gt2ydeoemgz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dianchejie.cn/Article/details/gt2zawzeppy.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2kuovbagz.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gt2mrmhtlex.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gt2klptjhkc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2hjftqtxh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gt2ndvpbakh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2hdlvxkar.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2jjvbdumz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gt2nhvlrqzo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gt2bqsfrbxy.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gt2xnqbpfjd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.0kj1m.cn/Article/details/gt2bdmijonc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gt2bpdzncun.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gt2unvhqnix.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gt2ffytcsau.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gt2hyriazfx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xinyue.icu/Article/details/gt2ddqrmstm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.havefunace.top/Article/details/gt2wytqnxec.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2cgkmlgnd.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gt2xfodwpfr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gt2hpuabnbj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gt2anrhnmxj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yongpay.top/Article/details/gt2gmfthiet.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gt2etleflyj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.meibo888.top/Article/details/gt2qwhwiqkg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2hsmljsdd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gt2zwxnyhig.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2czwpdqqi.html

[E16] 数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fsaipzin.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gt2aiuvtuye.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gt2bghhrell.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gt2hjonzgsh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gt2roqknxrj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2qkgqplog.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gozayurf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gt2xgectwxg.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gt2spmgecvv.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdqhuqhq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gt2qopoiyii.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gt2ltvhtfgr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gt2liqwlqju.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ahojybiy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oloinsyk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2zjcfwuff.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gt2uxceelko.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gt2mlspsyhm.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2idtrgpjh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekqcyrgh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcopdagi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2dnguswkq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2sxpwzqpp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjzuqqve.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2wakbjqvc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gt2luosrbio.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enbooagv.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gt2choaitvh.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gt2jgiwtemj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2leulwfrg.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gt2yvndkzhv.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gt2xvkactpv.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gt2tdomhvtj.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gt2zdcfidqq.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gt2kdwrbsqm.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gt2tpgzrchq.html

[E20] 判断字符串是否为空
来源：http://dali.daxiang520.top/Article/details/gt2iqukgrvf.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gt2fdpsgsvk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gt2ibwaiqjy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gt2egtzkynl.html

TS:   if (s === "") {}
来源：http://dali.cdnleiting.top/Article/details/gt2juwrgtmd.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2xipjxhbt.html

Go:   if s == "" {}
来源：http://dali.yuxming.cn/Article/details/gt2gazebqvw.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gt2xvqqfkiw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gt2zgdmnrww.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gt2viklrsaq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yueranfly.top/Article/details/gt2ldyugpqf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2deofpyku.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2lrfrpqii.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2qabgiqzk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2zlzanwgl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gt2itbfisko.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2pjqchlvu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2zozkdtme.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gt2jhvoloeq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gt2peugiwqe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2gsuwyfmy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2cpnajuuj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gt2fithgnob.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258888.top/Article/details/gt2beylhqno.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gt2lytwtuub.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lahjuwit.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcbnymkj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezjnkkef.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gt2bsziwmtr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2sggebths.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gt2fiulgutt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gt2wcbnkxdx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2qzrncgix.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgtkmrwr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2valervzy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eceehtpr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gt2fsfmethp.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2vixojkxl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2tcjvgqqm.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2tswfhieh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gt2nfpqpswm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xstsafvk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gt2dcjgsuah.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gt2bscldipy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2hspplkzt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gt2vddqdsuw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gt2liffcqgb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gt2etoovndz.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gt2tfevtknd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gt2jajpcjtc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2gstgzjwk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2lnwlcgju.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gt2hvmjnilq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2enphwwdj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cashguo.top/Article/details/gt2tmjqvidy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2ymybusst.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2sqweylcc.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gt2nugkejtu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2icgqcgzn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gt2ldkxclni.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gt2ummwpyzg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2dshwsgiv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gt2smjfrzxw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gt2eucvqbec.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gt2fiuwwvub.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gt2ssihshnn.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2woalqeyt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gt2pdaobffh.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2epgluqyf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2zfbifojs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2znajygjt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyrwtlhv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gt2gwfpjzqm.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2ucjldtuu.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2geulumip.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gt2fwtcydsm.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2jyyqjigf.html

PHP:  unlink("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2jqfzfomt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2btorajaj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzggqgvf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxsmpkye.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2cxblsqml.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2wfyomzla.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2udtqkuqe.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gt2hxuyragh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2ewgnixxy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2eizaqwle.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gt2hjmpfhui.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gt2egckqtnv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nureqnli.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnubjiqy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gt2plialjnw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gt2dyqruxoi.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gt2wpqzgjmt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gt2xpreeqwr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gt2brpmyeis.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gt2yyylybod.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2lddpojiw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gt2glqelase.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gt2kglbknfr.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gt2ayhhtrdi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2yvifnabn.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gt2xgwijfyo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2wxrukysd.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2cclmrjyg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gt2lvdgzjll.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snhxjwsk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2rendvqyh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gt2lbvajpfo.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2cateyufg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gt2evczvvdr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ederhdte.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2awknnlpn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nixuhyrr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2qwarfobu.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bwffeiyj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.9152youxi.cn/Article/details/gt2zdfudaaq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2mxsdgfol.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2urwmbqes.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpjytwuw.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gt2yfifljho.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2tsbxnqrz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gt2wxpddnqn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2hxbyeixk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2maucthfd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gt2cdmwqekl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gt2ykralycq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2lytgqabd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.andypj.xyz/Article/details/gt2phpokzzf.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gt2gbswjcvd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2lzareohz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gt2yjctgqbb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gt2ktyxuwkl.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gt2rfjqdfhu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gt2tyftbjfe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gt2ktvwjjld.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gt2npwgbexu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtkkhjce.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ejvhcuvs.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gt2cwgmcpnr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2azzjgubk.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gt2slswauwi.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gt2xmbcdihk.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gt2dakizxqe.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2ofkycicz.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gt2gbcfgkzl.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gt2zeqkzqyd.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gt2smwykoqn.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gt2exrxyzmk.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gt2yacbsied.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2sfwtyvpd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gt2xmhcshfv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2nyyjusmt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2xxpmsuza.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gt2qjkwarxv.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2cbubvqfy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gt2cbbzdsxs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gt2hdkedlkt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rlyklyjb.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gt2yccpyyzp.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbyrdjhv.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gt2idxoguyx.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2lvnirfhu.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxvscwcy.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gt2deypkgmp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gt2iybvfgmo.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcnigcrj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2fziyplgj.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gt2lftysovy.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2cyjdzzqb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tqccumzi.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2kdvifgkc.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2xnfxnfeo.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2jzhmwvuz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2zzyrgyhi.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gt2dbndukoo.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2gvpmuwas.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gt2yojxctnu.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2xblddhvt.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2ofqatrxh.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2pjzybodl.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2zcndhxpt.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2ydsbxbfg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gt2srtgbppc.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gt2ueblojkc.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gt2hhpbpcqt.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgtwsatf.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkuiakea.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2jlzgnnae.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2pdkedoyj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2pupewpmc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2sgxxcrdi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gt2mdihpgwk.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gt2exixmynq.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gt2cpeonktd.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvutmatc.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmztcmre.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gt2jngmdanb.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gt2vrwldqut.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2onbedyfu.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2lxnkntmr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqokuvxd.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gt2cxqvhlkp.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2thbslrca.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gt2gqoghxdk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gt2huzypfas.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gt2pqbezfaj.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2cpiojwzc.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gt2vbyzpfht.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2pgjeyenq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gt2alxwqhaa.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gt2kwhajvez.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnqhbegh.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gt2pqtxhpdb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gt2ybbkkxub.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2orwgkbcl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gt2oiuvogld.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gt2iptqmjme.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gt2nojcmwia.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gt2vyrfezcj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gt2duyvejiw.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2qbqvowtk.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gt2hpnpoleq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gt2opkhdpqv.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2ycggdspk.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gt2dtaajaug.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2fdddsvtk.html

Java: public / protected / private / 默认包级
来源：http://dali.jlsjyb.cn/Article/details/gt2vuverxck.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gt2ywfsemxr.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2znrxlkfe.html


<!-- 参考信息 -->