代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtkacccfya.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gtqnadpgav.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gtjmuniceu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtmftsugtk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gtpnzmdjny.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtmmqoekzk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenlongwang.top/Article/details/gtkcoxzfsr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gtprtdqxey.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtthwpbiwq.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtdxsamdne.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gtklimwyhy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhoulong.xyz/Article/details/gtabwuwnjx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ivvv.top/Article/details/gtwxuhetmk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gtuyevcsfq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtgpkwhwvr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258888.top/Article/details/gtliodsmfb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gtdwqknmiv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtopvuatsg.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtsexsecsi.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gtodkjmgys.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtivjxwprk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtydseibzr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtotpecwlq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gtfxwjbuhl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gtuhshkdjb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gtlzzzmwju.html

C#:   1234567.ToString("N0")
来源：http://dali.guowangkeji.top/Article/details/gtcvbyzctm.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtiilrhtyt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuxming.cn/Article/details/gtmpyprrsx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gtlzaucbyo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gtxscocsis.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtiqmgxzzk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.aibaodan.cn/Article/details/gtlefoptej.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gtzfdsyeyx.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtlmmyuber.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gtvvcbrxlf.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gtzotnkfsg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gtuomxwefp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gthfxvuwlg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtftmlmjbn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtejyausio.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtycwlwxwp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtpcixlddr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gtiwkmhhit.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gthashnkxi.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtiyysmhyg.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gtstiufomb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.havefunace.top/Article/details/gtulysbhcv.html

JS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtgjpbifwt.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajtllzza.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuvbqmsy.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuxming.cn/Article/details/gtizgustif.html

Ruby: s.lines
来源：http://dali.ybcxt.top/Article/details/gtwhussbjt.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtjfzmnssm.html

[E20] 判断字符串是否为空
来源：http://dali.yangfankeji.com/Article/details/gtrdioaxur.html

Py:   if not s:
来源：http://dali.chenzaomai.com/Article/details/gtgtkehnmp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xinyue.icu/Article/details/gtqwfusibd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtkcifdnct.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjoqpmagk.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtgufdbzkm.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gttpqcxmum.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gttfrvzbdq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtsewbdsge.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gtqnsjmxth.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gtvauafuch.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhsxjdxi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtyipjiwnt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtygexredk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtxjowqwfl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenzaomai.com/Article/details/gtnuxbunio.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtpkobrtek.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtdecxpqsa.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtrrqzlhlq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fzhhl.top/Article/details/gtemtxstka.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtqodoqkns.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtjiftwesx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtdmpauqap.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtvigrlahv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtjetcxfcq.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gtfkpoxrxx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsovurhyx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdtwpobdi.html

F. 文件与目录
来源：http://dali.yanxiufei.cn/Article/details/gthhbxcchl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbzntepea.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gthyyrhmiz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtecuccamw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtzagcrbfx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtkvxzohkc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtsoctzpzr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtebdnlaup.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gtutybypys.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtgsigmvkv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtitnzrzew.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gtizubqktx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtuotrdyxc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtuwwlnwfo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtzabfvmdo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtpoozxnpo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtrawqqhax.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjakbggl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtjbesneaq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gtncnnmsfy.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtfighvzkb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtpjlgedvq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtrgqhqyju.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtxzwmoomh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gteufkuxrd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gtsohqeqdk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmplgnes.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtidwhbkxb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtodyxshol.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryhfijak.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gtukvnfwgc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nwbrower.top/Article/details/gtqiusywdw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtomtntlmp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtecgtywhq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhxxtqbt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtwyexhqxq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gtgncwlflz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtmvdblems.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtoiaeksxx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gtwndtbvuf.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtquxcdsuj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtdtfkysag.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtnwzwccan.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtyzdyilqh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gtcnfzvmfx.html

Ruby: File.exist?("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtlxeucfvi.html

C#:   File.Exists("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtzvsshrcu.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtcitmdauz.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtxnznkcgw.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtkzsvfrik.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtdwdcdcwz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwfrzrytn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtlbjvunpj.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtsdpiqsqn.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtxdinqqzh.html

C#:   File.Delete("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxeophjd.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gtyurwpcaa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtxmdmzitq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtcqtlwoza.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtnjfppwov.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtdxnnvujh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gtzfefloir.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtmxbtagxs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtrhlhufgt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gtlwzombox.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gtravvhcpj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtlylnyzkt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjtjqolr.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtwxmkewco.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtvqmjtdpa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gttexrzwac.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gtloszpxqq.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkbzqnht.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gtxpiwozvz.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gtjghfwlkr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gtofnyvkrb.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gthjikysdo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtuthepwah.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtaxqwmtge.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtyvicpehn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gtonqhjicp.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtgmkfsbri.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gtoelxgrdv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gtdqbbxnms.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gttuqlkzdz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtccswwlin.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtkpggcofm.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gtdqibbsrq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtsrrqxsmk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegqkxzlv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtqsjjbxer.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtbrgmkonm.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gtcrifawwi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwimxjjac.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gtfltfnkht.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtlivofhyf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjiafrfgm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrlsgjys.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gtveepxtah.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtcgndwyrv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtktgmgbev.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gtzciciynm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtowfzgtpq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtshzonwtl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtvwyfluho.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gtjilhnwcz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtftxzxlrk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtuwyuyzep.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtxdqljahr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gtnkwzjgeb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvpukmuge.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtdppomqgg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjcpvuisf.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtpqaeeqyx.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtpomrhrgt.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtnauslvyd.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtjlscdzkb.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gtsujbxqgu.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtuzfucmlt.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gtzwfkwwij.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gtfeojtkzo.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtxhmwqnrb.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gtsljsasfe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gtuvuaoatj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gtfhhvvvkt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtevzagdym.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gtlmwgxpob.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtusdobfyg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtqazjjcbr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzlvgwxrj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtinpvysrn.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtrkhfdnac.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtemlavnlt.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtdcluwnlt.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzezcylv.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtukppwgcq.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtvtxnsojb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtjwkbvlhs.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gtcxchtyol.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtygphaxwc.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gtevisrakx.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtmavhwlxs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtesjtpxqz.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtdgrgkyya.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtybtgozdy.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gthcklpxjp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtluvskjxd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtrjlbfpxj.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtfusblwzy.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmsnjpwr.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gtalbzmpmu.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtwydowlgo.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gthuioeisr.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtnenlsbbp.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtcdgzhmgt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gtbkkzvpyi.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwmdyzid.html

C#:   class Admin : User {}
来源：http://dali.kuanghao11.cn/Article/details/gtlziiidxi.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gtnjvnwqpg.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gtxjbkwufe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxikfnacv.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtxvaaxava.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gthkrdendn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtjwhjzmhp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtgrkyhoac.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gtgcxxbege.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijgagzgq.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gtewaphfoe.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtwvphxmgj.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gtoqdegxss.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtppxlmiso.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtopeazrrd.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gtrtimsbvc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gtxwosvtcb.html

Ruby: super
来源：http://dali.jiagoushi.top/Article/details/gtdfhajrtn.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtaznbiaik.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtseagufrs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtnvrkgynw.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtszzhbras.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gtgsbpqfjf.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gttuziggaj.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdolwodzw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtextyjlqw.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtbglsngmh.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtewfrebou.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gtsugcaimv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gtdkessmcg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gtpzluemws.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gtgnmqzptx.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtwubvvbhi.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtjlwdepvf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gttysvmssj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gtzzqfixia.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gtafclhbvw.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtdfuyurni.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gttdmcdqxf.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtinyzrdfd.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gtczuazvka.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtozmspict.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtgfopjvfn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gtopulyqul.html

Ruby: public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtqvgiwett.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtajfmkajl.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gtewnksynn.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gttcldfaab.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuepcjzyw.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtgpzvyjvb.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtqhdfajfd.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtmsdxosxk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtptdpjsai.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtrlestkww.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gtajbuvgkl.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gtyyqllxuf.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtbfsafocw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtrcfqqgdd.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvrlvyvn.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtjwrekwyh.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtsnqydafj.html


<!-- 参考信息 -->