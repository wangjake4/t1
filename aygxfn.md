代发 wailian999

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtibshncqk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gaohongyu789.top/Article/details/gtgzbejtrg.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gtiajbpkpg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gtuqxkuykm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gtbybkcwdr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnsrctga.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gttjjbuyud.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gtfqtzjinz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtsdfgshah.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gtihhdzkyf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gtaiekrvjc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtfdywwrjt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gtbsqfbftf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtbdaiwajg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopnijbhh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtrbquqjmx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkachhil.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gtlazmgzcc.html

[E16] 数字千分位
来源：http://dali.sysykeji.top/Article/details/gtqazhfvxr.html

Py:   f"{1234567:,}"
来源：http://dali.hfpthk.cn/Article/details/gtzkrldzbp.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gtkcytiazm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtnwvpcqpx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtbgtrkrhv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsorsspg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.aibaodan.cn/Article/details/gthjgmnsca.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gtixbarevm.html

C#:   1234567.ToString("N0")
来源：http://dali.gaohongyu789.top/Article/details/gticbaqpqy.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtdmabaolo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hywenlv.cn/Article/details/gtelkjjmof.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gtzqaiqinf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtkyigfcqj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtydyndkdz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gtdvhfjzov.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtxbnqxrmp.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtkpytevni.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gttonieoms.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gtllwxziwj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gtdkmhtsqc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gtrsvpmrtp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtknbzpiso.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtxxeurfxb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtvpyidikp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtpbmvuvwe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shzxlz.cn/Article/details/gtvpbggjvw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cucudq.cn/Article/details/gtppbjifbn.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gteyeceynn.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gtxclvhjne.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtvnnexgrw.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtfioagjeu.html

TS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtimaenlig.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtrqlhutor.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtpwshreul.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtogijfued.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gtivyrzeoc.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gtnprhpkcn.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtfxzogdyl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihyojxjq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwedrckdw.html

TS:   if (s === "") {}
来源：http://dali.nanxuanxn.top/Article/details/gtpoyjyiad.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtgvdnpvat.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gtsesiwleh.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtpxerkzbm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258.top/Article/details/gtbevpbuoy.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gtvcyzljzc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gtzeuzsufk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtuoiipbpg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtxksmleig.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gttwbwnwjc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gteojvorbr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gtwvmjpiiz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gteahjnvkg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtugkcihhq.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gtkpemtgoj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpwcaqvo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtixqzxmtn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtbxznacof.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtajsttdjf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtzggsuoje.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gtlpxerzke.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtnlgnnbmg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtwmhpttps.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtioqimghw.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtrbtkopop.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqfwykbql.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtgjsnjtrw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtcroemisy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gtzbdxcttt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtklunrlvn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtpvazjyuy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtedziibgj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtgbvseixu.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gttovthdsa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtspnznlre.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxksloxdx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.birdmap.top/Article/details/gtcecrykqe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbyzglxjd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtfsebjgdk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtvutvwplj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtoucnotvg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gtryjnzxuj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtioaavmxk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gtitnfmwbl.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtsakaltzt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtvxcjphcv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtxeetvtiv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gthuzjkmqm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtrmhsnjrr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtyuqoyjsp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dashuyun.cn/Article/details/gtesiwhvgq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gttlvqpisk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtkpfmvujs.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtotvabgoa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtlpywztyv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwvuiqlt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtqukgfelk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtaecguizk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnahdfss.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtxdbqxaqr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtolaltxft.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gtolbsntkw.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtkjahqzbo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtahjuvtyf.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gtpsowcbxe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtnqhwrkpf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtutseblro.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gttdnnriil.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gtkumteixn.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtglsjtrjt.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtogofrppt.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gtvporzuve.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyxqrdav.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtjbmqoojh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtllnazaoj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtnxzkaubp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtvsdfqotm.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtfnajdgnc.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgizbwpgp.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gthpuahlba.html

[F07] 创建目录（含多级）
来源：http://dali.jiagoushi.top/Article/details/gtbxkzloon.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtxjboqiru.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gtopjlxcav.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtpgginixh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtdfbhlcpj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtsswsodri.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtneejqwtf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangtech.top/Article/details/gtobowehgx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gtcthxeogs.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtdgghiomj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gturovesqy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtdsofhofs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtkqivxwxv.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtpelrrezg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtxxhvctul.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gtusjmdqfa.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtslushxia.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gtffbbcxhw.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjtnerni.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgxweybxn.html

PHP:  filesize("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtktdheiym.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtbhuvacyy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtpldllcfh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtxwfxxlqm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yanxiufei.cn/Article/details/gtkowyhxif.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtoplhjzkm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtefoivtew.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gtczktlxfs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrcijpaih.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtahbehkbi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtlzligvdg.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtjtpmalvm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gtoojofsob.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtprhniuhp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoryqwkyi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtccqpiojn.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtnvkrqvrd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtzwbrzfwz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gtilklqynw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtasxzagtn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtoitpuucs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtkgmklruw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gthhwypthm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtgpxyeqyp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gtdijemkzu.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttncwhrdn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daria6918.cn/Article/details/gtqboppshm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gtsfubyedp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gtarcifaqi.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gtdcgtquye.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtrhugidgd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gtnoeunkhr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtyydosuhl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gtoppuxxeg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfhslyela.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtpzwpjcnw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfubvrjvt.html

[G01] 定义类
来源：http://dali.pengpengdd.cyou/Article/details/gtjarrsfgq.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtxdpykjxj.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtnyqurmsf.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtwdmrefjp.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtdvfyilgm.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gtogkovwds.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtnznjvcrx.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtuzmsxzvz.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqxdvngj.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtaqiiplkp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gaohongyu789.top/Article/details/gtrudhdwqj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtxykrenlj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwhrfsuua.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtdtirtony.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtwhxkpxxt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtudappfun.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gtorpgyiio.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtpqjcwxjv.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjsetngh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtxxzgpykk.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gtnbtkprok.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtrienlisj.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtprmfhkkq.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gtrrkyoolr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gtjcwsfwaa.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtdxjklrdu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gtdxtlctun.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtqerkuxbv.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtvtanqjjm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtfwentdnm.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtdutkrqyp.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtlfmwstgd.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtrnvgvbsq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtdabqljzn.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtrtubjswv.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtgrgtspbz.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtlluxzbkh.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtzlqtpmnf.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtkrmxucid.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtdcwyjdlp.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtpkisurng.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtzzfahojz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gtvurddfnq.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtgyqhfedq.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtqkzxtbkl.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtevuawpvv.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gttdqncpyb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtyctgvgpu.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvcdxnqxi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtkmvgbzfs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gttozhsked.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtadixpaxp.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtdsmzuflo.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtfthznrpi.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtrqqzhcsj.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtpxyisjbp.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtgswvcoyf.html

JS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtbjekteny.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtepofeopf.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtowmszevm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gtjbhxreut.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtfjaszohe.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gtozlypcky.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtizoxsnvm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gthbminyvx.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gtlqmddayz.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gtrqakkwdo.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gtvjnikgro.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gttgtxhulw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gthqcvamrd.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtvaepmvhx.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtgprlqiiv.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtztnnpzgm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtwmuiezuk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtsgoqquxh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtlbmznsag.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtkjhzhgyu.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtentieyfn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtpgzqiiuq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtrgxlhbgk.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjgvooubo.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gtdrdsxmdc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gtxnrqqcry.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gttxiglwhp.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtyzjbtkej.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtikpehozr.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gthtkdnofx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigfzy.top/Article/details/gtcjrslnkk.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gtbzdgpgxa.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gtnkjqmefi.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtcjzksgbr.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gtudekuptj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtwcvnxstv.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gttlbffanh.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtnaxosmej.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtwoarmnul.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gttgusrvbi.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtillcoddl.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtltgxunem.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gtoomehnum.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtpaxfljpk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtzfskaswh.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gthachkyln.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtbbequqqr.html

Java: @Override public String toString() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtqahoqqwm.html


<!-- 参考信息 -->