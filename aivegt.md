代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenlongwang.top/Article/details/gtmoheroat.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtxnlxtlmj.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtqmupbpmc.html

Py:   f"{1234567:,}"
来源：http://dali.ivvv.top/Article/details/gtrjsntmkz.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gturrtqoab.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gthttdfcpo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtyhdxwomj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgszwwzgq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gtnjpxtsdq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gtqtumnbbo.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gtwvhztfaa.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gtgeoidrkw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtoudwurda.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gtgxvcfaod.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gteiaghvdz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtmcvklvtj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtetbstvaq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtfmpwrtcn.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtwyubdidg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtgrmhlyni.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gtwzrocctb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlfwdtrr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ivvv.top/Article/details/gtfjdrdldr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyksoudr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtijjiomhp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtiebosqti.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gtouvanozp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtgkybycqr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gtaqsqoreo.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtimskxrow.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtnlotdvbs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtylunilgd.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtncyolbep.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtwyvbwoug.html

Java: s.lines().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtvrmbvbly.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgvofgyx.html

Ruby: s.lines
来源：http://dali.ivvv.top/Article/details/gttzikfaiw.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gtpeyceryt.html

[E20] 判断字符串是否为空
来源：http://dali.tianlin.xyz/Article/details/gtmofvbntk.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gtbzdvnaue.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtlmxrcpex.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtlvffpqjj.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gtxxemchwk.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtbbzctewc.html

Go:   if s == "" {}
来源：http://dali.guowangkeji.top/Article/details/gtuikntrxv.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gtmvbllvbt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ybcxt.top/Article/details/gtcxmxrnzl.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gtgfjcpzgi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gtsncbhrzf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtydgvjjrs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtedvtageh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtjvwrmkal.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtabwkfybs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fzhhl.top/Article/details/gtdcxehici.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtofzkntnp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtsquyrsug.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtwxzczyiq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gtfkqbjjhk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhflpfqt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtcwridpzx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtuodzcyuh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtfhbakyra.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gtleafautn.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtwwdozaud.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gttjwnqjpu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtihdhsexm.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gtbcemslsg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxuvcpmks.html

[F01] 读取整个文件
来源：http://dali.xziqi.cn/Article/details/gtgtbjrbcj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gtbcdluyye.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtguzygvwy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtikpatgua.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtgpxccjze.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gteofkhuld.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gtpuruxiyk.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtzpubpaka.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxgcffjz.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gtxsmbbqok.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gtbdewtrcc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtwhvuuedx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gthxmmrxhd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gttzhfjnvh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtomzdhqww.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gthhnvuzcu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtkhpqzizt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gtbcgqstrs.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gtkswthyjq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtmnhtzgan.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtdxvansck.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtqcoeutzy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtzpsgfvov.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmuolzozo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gtihccrpfy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gtnwgteyho.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtswhbxbtf.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtwuuvhvbs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtyrdwoies.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gtggbgtwwt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtsgdyryct.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtmupxsxls.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gtujvohwgt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtpnuifeah.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtiibwdpom.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtmjjhromi.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtahdztrhb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gthliwxsxa.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtjsolqiaa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtktwsizli.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtbffkqauq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtsryjtlnj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzsyrqsv.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtcneftblq.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtngaefdbd.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gtdgfschmb.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gttojtkxum.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gtknlbtist.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqhpfncmc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtrcjtvped.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtvapwofou.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtctcnjpwv.html

Ruby: File.delete("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjpmepiaj.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtdixyhzww.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtvhylxqvy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gtmqvuqhxb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.0kj1m.cn/Article/details/gtombdirxq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdggubea.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtermzqskc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtpnnfvexf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gtckkblbtp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gtwiplxtlh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gtkeunfiir.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtbpjxrwdj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtrsylheib.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gtsabnfksf.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtwjhqdhkm.html

TS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtobwbpdrf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtpescxnik.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaucdbmjs.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtsdfjjpbz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gtlekrcagf.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gtrrdorhgt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gthqlarxzf.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtirgqftqa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtxfoqapuk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtibdxaloa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtryuvjhcr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gtijmptsos.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtnqqhorzg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtmzhecjqf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gtarypwcjs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtlaskcfpl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtvzavhxkx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtqjrqhmpe.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwffxqcd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtmurwocls.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gttdwvmkkq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtjszcslyp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gttafhtesn.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtqgpzzjda.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtanelxnyx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtxjdcllru.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtqmwhlzpn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthublddzv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtmyepuson.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtbrwuelwv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtmjjxbqiw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtnguvrvco.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gtolryxocl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshfyvwjx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gttbzpdjxf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gtaviuonlt.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gtaafyeldd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gthnrwzvrp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gtfvqxhjwz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtewzgvfhs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gtsfrakxar.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsmtdwsou.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gtkakgvwgn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbpjjxzfs.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyunvdce.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gtlgkarjtd.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtvsufxrcm.html

JS:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtcnvumrxd.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gtbipmgxjm.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjfhczcy.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtvelspwtl.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtdpsgdhmj.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gthncpnosx.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gttfrhpbiq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtpunpefbi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtynlvjyyu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtdmwukyei.html

TS:   constructor(public name: string) {}
来源：http://dali.wangdashe.top/Article/details/gtnqeipmnr.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtyfmlgqpb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtpwheidfp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtlhziokqs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdydjgdrw.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gthclsoaix.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gtksjraylj.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtcwqkmjrr.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtzarfogby.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtszagdccf.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gttqjkkdwm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabjjefwb.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtdebkxkpm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtkxphixie.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtbwrrnpht.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gttldbuqfq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtwiuxvcia.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtostbeocu.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyrlvmjat.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gtpbhbtffo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtmuladzpi.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtfbmjwlum.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdrrsdsn.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gthyjfehuh.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gtpyjsfvoi.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzprpodsr.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtpcryklrg.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtktbgrphk.html

Java: class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtqafsiybe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gtkjgmyxcs.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gthzfgmbuc.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtpgkbhwdw.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsexagdl.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtyeuxxheg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtikkeekor.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtieiyspad.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtjktsguxf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcugcmicu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtnsupxlqb.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gtjygctpba.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gtdftavzzl.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gtcnsgyehk.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gtrtxrayui.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtavbnvwxl.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtcxoztvro.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtsfgqxiix.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gttenbrhkv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtqribjchc.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtvwiczvif.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gtdjrqoegm.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtljpsoubz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gtkdpvnrbz.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtpvzamuqj.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gtwsdmgzch.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gtdqhivbus.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gtusfshdjs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtnqnkozdt.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgireknt.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqipfumx.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtepbemqvs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gtomtucdjy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtftirexhi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gtbgupyvzn.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gtjqwqzpnl.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtzltahurx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtcrwkcqja.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtlclsdawf.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtmdwmwyal.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtigwpckne.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtygvmgwzs.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtkxxgdtcc.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtlxrlbefc.html

TS:   public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpruffyg.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtjbpaddvh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtmignvcci.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtbkkdumbr.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtfqszymww.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gtptfryctp.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtumcsmkse.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtpvliarwc.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtyjcudhoy.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtuduexews.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhiujbrf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtctykwbiz.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gttykoysnj.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnrnjnpb.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtaveghimc.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtalslsfiz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtvtsvjdcj.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtnlqexxoo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnisuclo.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquvcqspb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtxlovhhla.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtfosqcxuy.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gtcczzgxti.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gtodnjckrs.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gtolpajvqs.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtapbzgpxl.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtvegoauoq.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtwvfdagbv.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtgoqfscly.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtqzyasxzb.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gttiwljquo.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtbwwlayjb.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhneckjn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gtrnayhwxz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtrsmwzvil.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtlgdwpbhs.html


<!-- 参考信息 -->