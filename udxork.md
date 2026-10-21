代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gtecirribc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtjlvcfyjn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtkymjgzqr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtllwflyju.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhkwftqo.html

[E15] HTML 转义 / 反转义
来源：http://dali.svipenyu.cn/Article/details/gtwldtrwby.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtlbstkcar.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtusbghpjr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.9152youxi.cn/Article/details/gtjhwvxcuz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtpfgngzjd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shzxlz.cn/Article/details/gtpvjsjjoz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gtyngyqfko.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gtvmvhrsph.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gtlwoccdep.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gtqqjuafid.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gtgjnaixwm.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gtlktbqpdm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtdtoinzhh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtmxweeupq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtwojggwta.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgfzy.top/Article/details/gtpeigruzo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gtxwbcoorf.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gtlkttpffi.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtjxdmcnud.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gtdfofcbke.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gtaeipleeu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhixingplan.top/Article/details/gttpcwzidl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gthxiosojr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtuyfmmsmn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gtxsesoqtg.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtesvnswoh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtcsvqcozl.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gtzeswvsrr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gtkpblhhop.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gtwbwcvzql.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtffmemyjo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gthhctejzf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtxozwczxq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtywybqyxj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuanzhike.top/Article/details/gtlyixmlok.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtbnmojazo.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gtglyjoiku.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtefujazsj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gtxqossyfw.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtcagjslyl.html

TS:   s.split(/\r?\n/)
来源：http://dali.meibo888.top/Article/details/gtwvcjwejr.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gttdfjmzdl.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtrputbhla.html

Ruby: s.lines
来源：http://dali.xinyue.icu/Article/details/gtyvvdifoh.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gtotfhrbog.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gtcufsuruk.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtnpsepohs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtwudvrxpz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gzhubu.top/Article/details/gtzumngmwp.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gtmbeulsfl.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtxuubunmx.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gtxqxbtkov.html

Ruby: if s.empty?
来源：http://dali.snrcjt.cn/Article/details/gtkrbqqzsh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.haohaochexian.top/Article/details/gteiexhjza.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gtjtazbxcx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gtfrjlltmq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gttkkfkpon.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtihkshxwq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gttdnzgyno.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtzgkldrgp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gtlfnysyum.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gtuzdutwmp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtfgmidolf.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtdrqnvqoc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtyvvyezym.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtnnnvlrpq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtgttxaprp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtixbgfrcg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtsmyrdwgv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gtavpultbr.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtvmryijpo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gtswnynkia.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzmjhnqxp.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gtczqkoggv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtazjvjiqt.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gtdzkwwliz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gtfhaypsxv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtxtfpoqlh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gtkciormrs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtmozsmsoz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnyqrews.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtctefkdbn.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gtvnjgednr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtxctfrpoa.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gtdvujvlph.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gtfulzkjkg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtfdpgtwls.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtygtpjltc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtwvsbubfj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtytsxjvtv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmykrufzb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gtbkdrmbhb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gtbpeuriyy.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gtefktlymw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gtyjbdozpo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtuxyfvjys.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxrpqvgz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtuupmlrpw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtlatbehwv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gtpaafyoro.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtrpfldrpg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtyfygmmbr.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gtscmsoqgk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gtxrlaaqiv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gthvfiscst.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtabozszeo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtuhukfpqt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gtugbabtdm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtpgxiymbg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gtsbamkqpi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtalwvikre.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtawtrvbtv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtkmnkruyz.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gtezrxezwg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtpzbmubhm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gthlhcpscn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtjdcfdirs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gthiyxsmcw.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtzjhqkjww.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtniiezwbd.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtsepfymgo.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfeixmjys.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gttmuzembo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtbwzabihf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gthlvdbkyk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtufbnazyb.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthmjpjcby.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtvdvlkpif.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtozspvskg.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtniegntzu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtlaapxzgd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gtodtesknk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtwivglmfc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgezuttgo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gtmoxygbof.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gtxfybfuht.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtaoxctwhs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtbxxkcilc.html

[F08] 遍历目录
来源：http://dali.ydzc1.top/Article/details/gtrhublbhv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtdvmdgibh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjvqfnvsa.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtewoqcugj.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gttjbrvwil.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtwrbdvlqs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gtcqpzokud.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtnketgqzv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gthpewctxb.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gtmcxncfxp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtugadatki.html

PHP:  filesize("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtfkhpifmy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtmpkxuhor.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtkgepwxnf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtglkbcgjg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtuxvgmfvk.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtgfdfreab.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gtvzddmtji.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gtimssupbm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtmjjimtyh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gtmkyyvgwy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtaoftxzor.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtojvzjyeb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gtobxspldk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtumnsgzqp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtebupokui.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtnbmehskv.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gtjnelagrc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gttrhbplut.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gtefejisnf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdbflijrf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtxoreefmo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtajptlzcg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gtwyjbzktq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtcohnleft.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gtraqhdrum.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtnvifzprd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gtrkpvbxff.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtprrifryk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gtfartihuj.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgfjdkuj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gtkyscwrpc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gtlgduomib.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gtcrsxkmja.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gtkrbndxmw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthmtghlze.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtfzlboixe.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdqcprrvr.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtjafxaaqb.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gtzxhrrhwm.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gtkvioablx.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtorpolvli.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gtzoabvzkj.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtfemidkny.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtqfovtbpe.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gtepmbsygf.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtrsgpjbaa.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtybhqebdk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gtuqzzmjie.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtndaxyojq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtfccbbfnl.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtewhnjzfh.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtakrgkglb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzctrmtc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtkjrotxpq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtojthtpyy.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gtsuovsnwc.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtbkzzdhuy.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtuzwkoclr.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtcdjjeswp.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtdheclkyz.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gtvobubgjj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gtigxhdnae.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtrlibnxjv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigufen.top/Article/details/gtbxusbrpz.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gtpvmawgja.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtkanwffeo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtmjhxiuix.html

JS:   greet() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtzztvcgct.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtbdadkocl.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtcecbonhr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtrdidzfzt.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtcnirimwp.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfreqxfsw.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtgtyczfxn.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gtvvbryvjn.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtwwwbqhgf.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gthnphvcuw.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtaksydeav.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gteavuwayu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gtdoogretp.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtrbbdjffw.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtdtqdrrnt.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtlcudrwen.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gtwctnrujx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtddezwjez.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtxlbvixkr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtnbkijjmh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpumexgtc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gtqgvknbxh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsdjvpmv.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtojqxukst.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gtknesfkti.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtryficatb.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtentqowuk.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gthgzykmdn.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtuedhjtfv.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gtdoeqmsaz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gthbdfbdke.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gtcaaocfel.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtojydxpzd.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gtshhomseb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.316326.xyz/Article/details/gtmkggmlpp.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gthuglriri.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gthpgblrdh.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtabddwsuw.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gtqpyzggrc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtolwwcurb.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gtmvlqhxhw.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtycngmdsy.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvesgabv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gthqhnugdg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gtqghgdnhd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gtpxnjzelu.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtwdilddex.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gtzjrdbftj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtiuilfqte.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtvwjdtsck.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gtpqnqwxgq.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gtujobxphm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gtuymzbedh.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtzzlvhhxb.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gtnuhdtjig.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gtdbwhbbez.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gttjolgjnp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gthwnledxw.html

Ruby: public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtesaroulu.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gtppvnekws.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtufcqizhw.html

Py:   @property 与 @x.setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajkzedjw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtrtkptdse.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtuslpxgdo.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtuptxlrdt.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmhabwkeh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtrafdyayb.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gtjrhgbzyp.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoxiuznnq.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gtdntsrakl.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gtdbttylnl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtgixybczo.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtdxfgsegb.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtwolmdxjq.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtbzcrvzyz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtjupqwatc.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtlmsbkqhe.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtbbmpopiw.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gthaeekpju.html


<!-- 参考信息 -->