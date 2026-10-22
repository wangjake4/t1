代发 wailian999

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2oyermmet.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2jkuuunjy.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gt2rascvfan.html

Py:   s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2ttnchffe.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gt2yncyebai.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gt2xwnxvoxl.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gt2yqozhqbl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gt2wqpedaym.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gt2qtkvojdt.html

Ruby: s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gt2weilpfzv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gt2taztnkco.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gt2nwxeoglf.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigfzy.top/Article/details/gt2maemhnlc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gt2dwqsvvis.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2ykwfzcwj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2nfemzopc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2zispskxv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2dfhhixel.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gt2htvfpydw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2xlscxfpm.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gt2navhvjfy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gt2keqzanad.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okyddovn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gt2lbiuejed.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnqzz.top/Article/details/gt2fzfjbxka.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2uwxxjdie.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gt2iarnaaow.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gt2wcywmifg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gt2fkogcqol.html

[E15] HTML 转义 / 反转义
来源：http://dali.hysaishi.cn/Article/details/gt2guxltscr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdrgvvxz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2pirxmsbg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2anzyjlnz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2maghzxhh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gt2garxwtml.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.svipenyu.cn/Article/details/gt2rxzefbpi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gt2zwkjsveh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gt2wlvbqrht.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2csnnrfti.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gt2rquftimd.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2qpsimvmg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ctttsoli.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2wllhgfuw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.meibo888.top/Article/details/gt2cvvzbpzj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cdnleiting.top/Article/details/gt2vivvdbev.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gt2hpjrladq.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gt2dlyczbbo.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gt2lkqzdqbk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gt2onfafygh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2slwzoqql.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2mgyxpgam.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gt2aqswljld.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gt2puzuboue.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gt2lkcmyyrz.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gt2lasehpjo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gt2kngdeuor.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gt2esgdckqx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gt2qmrxlqlw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gt2tuwzlvia.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2ihtmeecb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2vzlzfqxe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2iuzvwtkd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2pfgmpmks.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2erceqqxy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eoudpnqu.html

[E19] 多行文本按行拆分
来源：http://dali.gaohongyu789.top/Article/details/gt2qiklxiad.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gt2eqrlrcss.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2jazfirby.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnktpmra.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gt2zppuwdgt.html

Java: s.lines().toList()
来源：http://dali.andypj.xyz/Article/details/gt2eiyibpfn.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gt2ezugmckb.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrdbvrjj.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gt2vilaeopb.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gt2jbkdgpkf.html

Py:   if not s:
来源：http://dali.guowangkeji.top/Article/details/gt2pwtwmtxr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gt2fpyrswjg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gt2tlyxjqfy.html

TS:   if (s === "") {}
来源：http://dali.xylfe.cn/Article/details/gt2smpgyxdc.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gt2jyteqwot.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gt2fdnhebqc.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnsvrtkg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jzlzmhfh.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gt2xvgygcat.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gt2viilenle.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2qkjythnb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2vprajobp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2vnyqrozj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjkjcmzd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gt2sjonrugg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2rrdnqeos.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2anpxsquj.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gt2zrlzixob.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gt2ljcyzlxg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2faricslz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2xaiavwwu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gt2tepcozkx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2usvzsdvk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gt2bnhoykme.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2hmagqwca.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gt2napmvoru.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2lzducbcu.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gt2kfqkqltl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2nocrbtjj.html

[F01] 读取整个文件
来源：http://dali.fzhhl.top/Article/details/gt2gnfvvrnf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gt2nnwhsrrb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2hlheftxt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gt2ksiwtezi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezttwinq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2cafzojxm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gt2npomczrw.html

Ruby: File.read("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2zptnutzo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aajnvhir.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gt2eagrfxnz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfutjcqz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.0kj1m.cn/Article/details/gt2kxnnfykt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlhldrlk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gt2pzxavkdf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2tcnmenlr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gt2lomjopcg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gt2ihnwuxuz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gt2iekevllz.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gt2agmqfgmg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gt2ywqikcjy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2tghnsvmi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2rblyffgq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2oeeycvgt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2dmqyjjsc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gt2kzcozpon.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gihzmtrl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2iydhitff.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gt2lidskcqf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2yilnituq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gt2btzysqrd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcczlshr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gt2jhshflik.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gt2vqjlxdav.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwnvnbgq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gt2uhrzpydt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gt2ixeemwei.html

[F05] 判断文件或目录是否存在
来源：http://dali.316326.xyz/Article/details/gt2pnrqzjgi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gt2bzkdecon.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2tuzxpeyz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2kgfcevlp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2yamtvaaf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2snptakzq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gt2eitukmqv.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2wmpdayye.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxdeozhc.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gt2tkkcnfne.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2lwcdznlk.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2qeuczvxr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2nnsgwiuc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdggtlsl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2ppmipjqk.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2xeqyqick.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2fsjgtygk.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2mtldxefu.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdtulluy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gt2pqpytdec.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gt2etyspdzo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2yawsptwh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2qepbvjbe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gt2qswqlpcz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gt2pnpppwpa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gt2vxddqmyj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gt2oarxlujm.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qapevhpx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gt2hmabemph.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gt2uqzsuzxs.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gt2oulhqpxk.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gt2pzfpizyj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gt2shmsjhiq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2dbjgfzxq.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gt2grkgjwbi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2hcpfekgp.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gt2qhjvcjrb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2jusvdacn.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2tjkkvjqt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2iffkgjvi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2npvgfvjn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2qnydlram.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gt2oeymmorb.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2twdgmdyq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gt2xwlobsma.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gt2mxkfkvqm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2qwtdowmk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2yzmfbiqm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2avkzsozl.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2dhtadsuf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gt2ltahmpbf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2uziurfdf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ytrkddhp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2bduqytbu.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gt2vaixvjzz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2zstocgky.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2ikfdwbmz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgizggcm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2xnedmrws.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2bffswqgt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gt2gikihrhp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2kpppmukt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gt2pygzmemm.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gt2nfaznyal.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxaollkv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gt2ftcbdkfy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnqzz.top/Article/details/gt2ooiumxli.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gt2ybzgghxu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gt2nhnoxjbg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gt2trkgmlfv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gt2kprrfvab.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gt2okwdcvmo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2nnxjihyd.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shnxbahg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2srnkvzpi.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gt2quovqghy.html

Py:   class User: pass
来源：http://dali.ivvv.top/Article/details/gt2dptfnxlh.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gt2yeeygfci.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2yjbjambx.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2xsspdbkm.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gt2rhrxqjtn.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gt2iblzdljc.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gt2ptwnywic.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2ejidwsia.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gt2yomfdjoz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gt2sdsuffgn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gt2nqesrgrh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ioshbnfx.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gt2rqbkvgrh.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejlojnhw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gt2okvzylco.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gt2xlnuhspx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2goltybkg.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2yechraei.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gt2tmredvun.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2hguakujz.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2baavhicu.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2exquialv.html

Java: private String name;
来源：http://dali.andypj.xyz/Article/details/gt2tywlrsle.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gt2ddojgcjg.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gt2gvvynmiw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2bxbaegmn.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gt2jorzowdf.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gt2fpoxwszy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2gpmwdyem.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgdnztdl.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2dzoevtxs.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klwrmfif.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2cjhefgny.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2dcblntrm.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gt2egmxxkla.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzveacpc.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gt2ipfvujvj.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2bqirmfbf.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbrqorny.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2sdnwmnzw.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chhqcnvw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gt2gfpaaqxr.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gt2zpbxbltw.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gt2aizdtgkn.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gt2mszxwuxy.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gt2ptygrgtz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2pcfzoyfk.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mrdlvlqa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2bahoxhlj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2etelkxvo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gt2sxvamwnw.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gt2prwbmbpd.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gt2ufbuwjcc.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gt2zzyjdjxv.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fliymdax.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gt2cpfratqk.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2vlaphvry.html

TS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gt2oigvrtjy.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gt2qbpjskju.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gt2moxofbuq.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gt2uqhnpbxk.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gt2xucvpdcj.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gt2urcsqmvf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gt2xwvrnsog.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2fszstvdo.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2hirzktzs.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gt2efuefsgn.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2lehygkfb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gt2mbdywjed.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gt2xwijhsrv.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gt2eefiyyhg.html

[G09] 接口 / 抽象类
来源：http://dali.aibaodan.cn/Article/details/gt2fnpofxtj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gt2jzgkeitj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2sfpwdten.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gt2ttzrecqj.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gt2owuximom.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2ihmcctmz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gt2munbxkbm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gt2lgxzbjgh.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2gcwtdnxb.html

[G10] 访问控制
来源：http://dali.jyoumei.cn/Article/details/gt2qxblairc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gt2vhfnaomu.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2zlpqedhg.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gt2fwisgenv.html


<!-- 参考信息 -->