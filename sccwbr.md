代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.sysykeji.top/Article/details/gtffylxzas.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmtofnwnj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gtjzmjqaef.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gttnamjevt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtvixraail.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtktvsouee.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjdxhtag.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gthqgbgxfp.html

[E14] URL 编码与 Base64
来源：http://dali.daxiang520.top/Article/details/gtcneqypni.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtgfnwqzen.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gtbmxtxlxd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtcaluyjvh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtyrhmsazz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtmajvvfjm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtsadtobiw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gttzcvruhi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gttfcznvcb.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnqzz.top/Article/details/gtvtldvbuv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gtvbhgjjun.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gtxziwstaj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinxxnoil.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpvppnzl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gtedbokocq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gttybstlms.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtcrjyqguh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gtbjaophkv.html

[E16] 数字千分位
来源：http://dali.sxryk.cn/Article/details/gtxkumbadw.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtujupvmmi.html

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtyiybntrg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gtfgxyxrwh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtbtmyjuva.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtymbykwwc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gtdjknvuov.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gteafuanmv.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gtkqbupmzb.html

[E17] 首字母大写
来源：http://dali.9152youxi.cn/Article/details/gtuuqesyis.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtvcduagnn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.haohaochexian.top/Article/details/gtqwdfsfca.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtfmomemtg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtwwrlkdqa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gtuhsqffyf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtcdcftums.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gtzpjxagwb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtwdepuxuf.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gttmnoyekp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.redwolf501.top/Article/details/gtadnaywun.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtixwcufmp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gttrigowiu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtxwgzwlaa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtzphxulrp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtvupvybkx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gtvsbssbvr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gtmdnckhly.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gtpqpwalpl.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gtbkblfjau.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fzhhl.top/Article/details/gtlsaywpsd.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtshemwpbj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtiuzlsbvb.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtgrimywjg.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrvybunc.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxctqllx.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gthwnsuyvk.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtwsxzvzmj.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayuormle.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpolckiga.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daxiang520.top/Article/details/gtqrgonitf.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtbltofypm.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtnlgyufoi.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtzeghvorw.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gttfckgdah.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gtagwejbyi.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gtphmbilch.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gtejslelyq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtqkvturnf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtujbhuoka.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gthqzwfzqo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtoivhnqec.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gtmixdbalf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtbulyubgz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtsgpcvqou.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gtimrynynu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gtsokccwqj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtmaqvsecd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtrluubapu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtclyrandd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.andypj.xyz/Article/details/gtantfgnto.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gterkybwnf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtawwkmzga.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gtlkukekud.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtjuporxtl.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gttrztfpeu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtipcfgzch.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gtqruapnru.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gtcrzauxge.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtndwcabdp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gtpnuwmpcc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtqubgbvvo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gticccmqpm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gteqviwumb.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtqudkohcf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtyrercsxz.html

[F02] 逐行读取文件
来源：http://dali.daria6918.cn/Article/details/gtavyljsto.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gtaqltygen.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtymtxywox.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtmabofnel.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtjybivsfs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtvuwxvwov.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiwtdjsb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gtfcqbztsu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtnmfniawr.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtcqsjreli.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gtpbdndjej.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtfuoyfvxz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtepwwnbtl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gttfzzbayu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gtnetpelra.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtkatbpvgx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtiszvkwoo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtmfbyhpas.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmvriibv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtaiqkrqwn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtwwcvssaj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtfrecwizy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtglomvnxx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtnhuczlou.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.meibo888.top/Article/details/gtsvpoimvl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gtsowxtyzt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtwpwdbgqs.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtgzkkrlgx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtkbyubdpy.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtgghhqtcy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzhxhnwzy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gthdsaegoj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtvdqkwjrj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtldlssskl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtwazsvyjq.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtqrrwzdne.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gtsvcmjyks.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtjaqhowws.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtgfbuiedl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrfmblrau.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtjydfdspg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtkyrlepbp.html

Go:   os.Remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gttbpyeanm.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtttgugqjj.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhtyzyuc.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjbggnos.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtonbcjixj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtqxdthrxr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtjqojddxe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtyvfqqktw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtqsqkkhzg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gtcxgfzceb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtinyotwii.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gtjrjqubbb.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gtqmphgelb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gthpfaudnd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gtycybazaa.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtqtpflbun.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtkueixmmf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtalpnckew.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtkzfslaxp.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gthfuyrgqt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gtdbqpuuoj.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gtczsssrpc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdowfzuxi.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gtpemhgsvi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtyotiwfqh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gteovmzxeo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtliwijlmg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqdtjtrt.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtbrmvdwah.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gteftcdmil.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gtjksdkrpt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtigltiyps.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gthxlhqxmm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtavytyfwe.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtdroopbzk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtnwdzzyxe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtvckhfrim.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtzzyyirll.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtjoqzdnld.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gthntkanbs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtlveuhnet.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtvndrxfuo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxrgisazb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtqegzigcd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtiigxajmq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gtqsnufvza.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtbizitscg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gtsdpaghqh.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtgrbwkbsq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtwqdquvls.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtvywonzam.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cheryme.top/Article/details/gtqgvwobxi.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gttmonbdeh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gtbyjoujya.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtkqlxktys.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtuahlcgiw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldfwdoqi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtuwioerkh.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtiwfsomnv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdrjtvyfy.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtedgjpido.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtevvxwmul.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gteocnzqux.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtfrsgdftd.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtdqwiqjjl.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtagpxpufl.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtwgchnyjw.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtajtoadva.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmhxootnv.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gttirpwhrd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtffkpnxju.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gtdegyuvqa.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtanuojdmv.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtqabtcbtp.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtmhtugvve.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gtvhqduohz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtwudyaqzx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gtwvjauhgx.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtxekoblzf.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtghvvzbub.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtgtvampdz.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtcxkuarbq.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgqsgahz.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtfytrotkh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsbuarvx.html

Ruby: @name = "x"
来源：http://dali.yj20258888.top/Article/details/gtneatfdsy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtopbtkroh.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtpxuypehf.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gttpfeowtb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtrnmthvhk.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbnikteu.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcstdafxn.html

Java: String greet() { return name; }
来源：http://dali.meibo888.top/Article/details/gtmsxqlsfb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtxddvjjuu.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtternarvz.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtdiwpcumv.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtdstmvdhs.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtbflbwesf.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtctssevvl.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtkqxccpiw.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtoddeczsj.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtdxkxsvvr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gthcswqwvr.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtroveoapb.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gtiymeldgo.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gtyhyzdodo.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gtbcizlnbi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtzplbvkjn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrgtzttrt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtovoymlrk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtoigfqtsd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtmujdwdcy.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtwtsolwsv.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpepfbiw.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gtsdlxtcpp.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gthslxuncf.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtrosxaqzf.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtcvbjkokf.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtjzqgniey.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtmccpjvqy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtdfxbabxs.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gtugyyqrap.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtjjydjumn.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gtbttrnlzb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtnaznzejy.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtlfmrbpsf.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gtuidnorkh.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtcefzrzeo.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtfwopfntm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gthetcpvhg.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjhuwnqn.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtdvruwibc.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gthfzgxotq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gtodsfuqbb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaaqheqvf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gtdwambwyk.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gtdwjcpwrh.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gtyitjoovv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtpvsvnepd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gtivgnnnhy.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtdpdkvbpj.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gtgezkmqze.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtocgwfzqv.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqytzajg.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtzigctedk.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtjlnrzxsi.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gtwrrpesfk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjraybcf.html

Ruby: public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtxephxkak.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gtblcvtgyc.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gttvpwfjcx.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtruqnmeyq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxmzniias.html

JS:   get name() { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtwawyfiry.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtavegxivw.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gthfkpbplb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtrwbygmza.html


<!-- 参考信息 -->