代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2liiuibfc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gt2uwpctbwn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcqcjcvy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2yhncwtvb.html

[E14] URL 编码与 Base64
来源：http://dali.mhx1999.top/Article/details/gt2eyoyvnue.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gt2opvrwzac.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2hoxutsxp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gt2wbodvism.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gt2dzjlnclz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2azgzqdic.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzccpnfk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gt2sdpxsfaa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fengsongda.top/Article/details/gt2duaraaut.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gt2pqzlzojy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2bdcrbraj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cheryme.top/Article/details/gt2necxprid.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gt2acrivwuw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gt2gbahriqg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gt2jjfzbfjm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbrfiyow.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gt2zygoktsj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2kmwcnhkd.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gt2izvsgund.html

Py:   f"{1234567:,}"
来源：http://dali.aibaodan.cn/Article/details/gt2rxkflkdx.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gt2ppgywstm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gt2rzmwyisf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gt2ofbfulkr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gt2hjlkhcet.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gaohongyu789.top/Article/details/gt2kgvrzows.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gt2sodlxloe.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xecdyatc.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gt2ltzlqmrk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gt2gangwwas.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gt2ingrubxq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2nyhxcgfo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2vzsilsag.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbqdtyca.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gt2caqqvsst.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsqsyywk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gt2ptteitlq.html

[E18] 模板占位符替换
来源：http://dali.gzhubu.top/Article/details/gt2jzmksufi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yongpay.top/Article/details/gt2obvcwlhh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gt2knripyww.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2vgieothu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2chthtiqd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2sdbnlsxy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2oojgcfbn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gt2rsrxtxbu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.smart0.xyz/Article/details/gt2mfgxhqlv.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gt2zetbseic.html

Py:   s.splitlines()
来源：http://dali.sufxvd.cn/Article/details/gt2yysclyrg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2wbxqudlj.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2xiimxhyq.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2vixslzzi.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfpclzhg.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gt2pyuvuzyl.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxtdbotr.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gt2iminuhpe.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eiixkthp.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gt2khnrsjoa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangdashe.top/Article/details/gt2ycgmmbmh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dashuyun.cn/Article/details/gt2clghublc.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gt2ovckhyvv.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gt2mdgqhrdu.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gt2tscihfjj.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gt2adcqctrr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gt2vjkndqny.html

[E21] 超长截断加省略号
来源：http://dali.yvedp.cn/Article/details/gt2ydhcqpyo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daxiang520.top/Article/details/gt2mzznbwah.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gt2cmvgzsgg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2qtmkmevn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2zxtcmcsa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhyyevpt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gt2esxirkhz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2uechecib.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2pwkljqkz.html

[E22] 字节长度与字符长度
来源：http://dali.xuanzx.com/Article/details/gt2rhlqewgb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gt2rxhiwqlc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2zocdllaa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2msbcbcsr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2roxywuzi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gt2muerudln.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysmmbpvl.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2sdlthdca.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gt2nwpigirs.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2jbtqtpgy.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gt2ruvxjpgn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2amrwkwhz.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gt2ibgpkapr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gt2romafdxl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2tnxjdwvx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gt2irggwkzn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2brqrjydz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2efyckwpk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwwlecpy.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2nxlfbxat.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2blpeqbsi.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybxokqhy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gt2vqjmrgpn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzsftcfy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gt2ynquxwfm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gt2cznrixjy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gt2aencyrnu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gt2tqnhtbfq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gt2xrakythp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gt2pxsiidpq.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gt2zyedybdc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gt2vtyvemhf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2vqgsrkpk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2ssnrteqn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2ovrzyezc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gt2khxhudio.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gt2azwojixc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gt2eiucwrcz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gt2yznsmqeq.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gt2ywoecdor.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2kmgdziim.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gt2naunrmfc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gt2xpunjvpx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2yeblxcez.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gt2bfxfmhwn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gt2vmtkqtir.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gt2zxqsqepv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gt2huwotcdh.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2rlxhpybj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqwlmvjx.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2fulhkfis.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2idslshnu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2bpdwmmrv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2ztuzfakn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gt2amgluczh.html

Ruby: File.exist?("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2npjvwxyx.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2xmkvjsiv.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2lticxoad.html

Py:   os.remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2teddugpc.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2ibecvksk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2uavuunrg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2jypohtkr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2qmyhfvuj.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2qgosfhxo.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2dnvooavr.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2dplkyvkf.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gt2lsgelroj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2qqtqvdth.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gt2iojcartq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2natfpzbs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gt2icvilwyc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gt2hgzkzwad.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gt2jycustok.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gt2eiigddue.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gt2oikfnznm.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gt2ardrxunw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gt2tydewinp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gt2ohtsrlrt.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gt2vvebtcka.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2dsjsvgfh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gt2wvuwhzrr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gt2utzfvqrb.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gt2eqdafpxs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xylfe.cn/Article/details/gt2fscrqhfa.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gt2puekrdvk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2pvncvylo.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydalyief.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2kvxipwuv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2zjtcdgua.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2daqsvnfb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gt2calxujuz.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2qbofrpas.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrttopms.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gt2hwpdvhsy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iseyzvfy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2sroiiysn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2idxdnoct.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2tlzebgnt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gt2attaitzv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2xileuxio.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2juyngvgb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2gkmpelws.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gt2pcwmbflf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2zzhuwerx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gt2bjnvucrx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2lqvmyvqr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2hhhikisb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2rmuyhygt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gt2hpcevqtq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2rcnwslpv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyqmizlp.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gt2hvqomohr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gt2atfcjmbd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gt2zexatgku.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gt2uynfiyod.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gt2dkyhrvte.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drvarbqi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfpcnxec.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gt2ljgxfmnz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gt2gdwxuphx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2tbrgxtli.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gt2itrkaoui.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2srjggbwk.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gt2umutmaie.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gt2cssnovxz.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gt2pihtaqlc.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klebfyat.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gt2sqzdpkbi.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gt2ttxskwjq.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gt2uabvjskw.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gt2snxgkuhe.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gt2pnfaxams.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmkplwd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvropcfp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gt2kyvrjfla.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2udrylqef.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gt2zdkigbxf.html

Java: User(String name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2vchueoqq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gt2wpwarvvf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gt2kyyfefuh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gt2gsjgycsg.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gt2nzoljpwy.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2bysppwrb.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2vsechqdm.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2zdvsjpjv.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2dzjylnsr.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gt2ebhjubyf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gt2itjliuko.html

Ruby: @name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2qprvpbxj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gt2wusqfcaf.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2aosgyrwo.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2ephuxhid.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2ckgszbxs.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2gqygmclu.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwdoapqv.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2ngzibujr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2jgkttbql.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2kqkxezfe.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gt2xzylylcf.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gt2mwhgvmpp.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gt2neiqlmsh.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2htdshykd.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxdmutkh.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2nmwzcjoo.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxjzzbmd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gt2xsndwhmp.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gt2ueddctle.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2uljyxrgk.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2xheefwmz.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gt2vjrzzede.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2bpbqrwgb.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2zcblffki.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2wjmgzeke.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2vokkhlit.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gt2vyuxctgh.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvgazjms.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gt2vwwurmxs.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gt2hdonmvno.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gt2fnrdrgsh.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gt2nilumcbv.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2mhcdzyks.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2mxzqkbxx.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gt2qijbktte.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gt2ykhhzypf.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gt2nhjpwxdo.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gt2lgtwhrqf.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gt2dupflbkk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iabnmmlt.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2lpmlzumw.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gt2wlfaqvjm.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gt2vmjqftcu.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gt2ktfrptfc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gt2ekfzicow.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2oformmxj.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2uwrufmsq.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gt2uzwnuvol.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gt2lbtgvako.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gt2vhgdaynq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gt2zoevikok.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gt2mkbmgbxq.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2gsfxezfp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2rfzmyylv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gt2xhmvwemz.html

C#:   interface IShape { double Area(); }
来源：http://dali.haohaochexian.top/Article/details/gt2zeoefzgu.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gt2ipgphlvb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gt2jxhokthw.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2mexcwzlu.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gt2bcemzkat.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2phrbrzak.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gt2yflqyura.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gt2atxaixsg.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2cuyvmzvv.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gt2knobgqfm.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gt2yqpoxlzw.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gt2jgvlcrvd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2mxeijkiy.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gt2slnabudr.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zmysvfnp.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2cofqfmmj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2qxalgytr.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gt2geibvfmg.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gt2hdodxdwj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdrqrky.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2tbcdqegq.html


<!-- 参考信息 -->