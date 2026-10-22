代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gtoqimrugq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gtigxfdndt.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtzdhjesqg.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gtykltptrb.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gtbmnsozbz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtmdscrtiy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtdplrwape.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtoibkcrca.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gtnwpjztok.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gtfwvctoal.html

C#:   1234567.ToString("N0")
来源：http://dali.snrcjt.cn/Article/details/gtspqgoydw.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gtcrvostun.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtzeoyhyng.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.316326.xyz/Article/details/gtkvksoqkh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtygwmsgvj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gtspddufgm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenlongwang.top/Article/details/gttrtjzxpk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtcjagnqho.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gtieycflyf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtgoglgckj.html

[E18] 模板占位符替换
来源：http://dali.sxryk.cn/Article/details/gtgmehptal.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gthmxhjtfb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gtuvicrhbu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtupyldagt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtzqihdknp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtbeeerynd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttibeuvwr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtqnpjqajy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daxiang520.top/Article/details/gtyfgavdzu.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gtbvfxjzty.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtomrmxbfa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtyiwhicve.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gthlinvosw.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtfbmzyjbn.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtytbnlvbn.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtvodoenmq.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtihimyrqq.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gtaetowplw.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gtyozfqbsi.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gtdnwynzke.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gtietjfzxp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gtbecgvpde.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gtobtmnwmv.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvpdtccix.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtldxozhhz.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtqazjsudo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtfscudknc.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gtrpophser.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gtsfrvgqlh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtdlrbohli.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtuccmgrwe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtmuclzkfb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtlyhgjyxv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtxpsbljov.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gteyygojgu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtcnimnevq.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gtbabmfnih.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gtpdndwrdi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtkfkseqgp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtpvbgbyys.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gttpumtxdf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwjcsfer.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtuqkzaqen.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gtfxrtcyue.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtqkxcbvir.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtawdbkzgy.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtgexvyarz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthvsddtjh.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtgzvdibfd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gtcoalpenz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gttrdtzidl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtftagikzx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gticlukifo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtnpuvzrug.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gtubbxshyy.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtkambfjhf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtwkavcsxy.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtbcraigoz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gtpcdipxiw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtvowxvafu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gthkcxkixi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtqqputyps.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtkmjohmma.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtqdavfhxe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gtubkprlvg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdwlaioe.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gtbfutooff.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtvacqiawp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtdbeotyzs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtfzwncbas.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtcesvtgpn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gtmlvfnyob.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gtqlnnzgbk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtbjzcajii.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtaozgaxyc.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtwjjuofax.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gtgnxyhqvw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtuncmkxge.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gteyjuntpk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtmiiqvhwn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gtarkhicxi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtclllazja.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gtnibpqptp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtbctzplbd.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtqendegft.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gtttpqwlqz.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtakvsnnox.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtyzfwtjxv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtsusbljis.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtxpbgiipr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sysykeji.top/Article/details/gtypnzqzcm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtbamgvvdc.html

C#:   File.Exists("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtbsmaxuuh.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gtukcllhob.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtapstqdwy.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtcsnwkfxo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtoojohmyk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxeysycqv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtmazeyhjv.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtfnpehbpn.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtrlimdiqa.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtttrwtotc.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtchajaiwu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtbdhqcocj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtcsxljjtb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtrgnznxzl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtaeqmtajq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gtfrgomars.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gtlyytzjnm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gtfucfssok.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gtpvvpulfr.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gtprhtfzal.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtjgnstiuc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.kuanghao11.cn/Article/details/gtuwpjieyw.html

JS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtjfhcgipx.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtlztixxad.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtmrxoyvgi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gtsvtmgoqp.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gteszxedhd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gthnwubgno.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gtznbphheg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtaqhmfzii.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtbnewqcyz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtunelpqse.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gttjblmuoa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtuhpyhxgq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gtanhaztfl.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtuxddxvjj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gtvzwaxbhz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gtqxumsaao.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlvvfpwcr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtvepmofzl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtwwdbwafa.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtgdnszzwg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtvgqttoeo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtgzpmbpmu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtrzevklpk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtvzmikzzl.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtkedygtsr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtqeqcdgsn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtxckveyrd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtivnoutmr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtopwaeqgy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtjlncitti.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sweek.top/Article/details/gtxzasitgm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtsaawcwpr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtmlklcvuv.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtbsoyctin.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaifdxhuj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gtnmcccntz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gtwhbwrhoi.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gtdbzkqsta.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtqziobpdb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gtotvvaubg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtufzffpas.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xinyue.icu/Article/details/gtevifpgja.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiephcnnv.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gtupwkmimp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlleqotki.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtxllbhcgt.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtcervfexm.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtmwxckpxx.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtsabjrbxt.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtezywzrtq.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gtrwvpidie.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtsgdodafp.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gtodtflluf.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtqbwajsro.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gthkpcpyby.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gtjgfmvcet.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtqbudodiq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gteeqvwidm.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtdmuexugk.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtcmqyyipr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gtjkwuyedr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtebfnbecn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtvotfhfjo.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gtumsqarnt.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtlumpjxal.html

PHP:  public string $name = "x";
来源：http://dali.hnqzz.top/Article/details/gtcjxnoxhb.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gthimstubt.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gtrkrjhrux.html

Java: private String name;
来源：http://dali.smart0.xyz/Article/details/gtgrsfkuoa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtgrzupcia.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtahqljepu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gtccaknhzr.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpngztie.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtiakwukmo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtturmjqlt.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtdjwzowhr.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtfsblzmlb.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gtoidmlksq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtwjrmnzxs.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtuhrciadg.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gthawlctgf.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtylsxerko.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtexiseitt.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtadebqdyh.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtrfrhzoac.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtuyotsltq.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtlswybmbh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtsodjembc.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gtycnoqrtv.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtwkltziet.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gtimncvmxa.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gtlfiqmhtp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtcwlglisx.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtoehquaaw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtuelcpqwe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtvtunyrgh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtvxvjzghv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gthinzskex.html

C#:   public override string Greet() => "admin";
来源：http://dali.nwbrower.top/Article/details/gtewxtqnjz.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gtiyalzizg.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gthwramhvl.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtryormioy.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtbwkhhcgn.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtjyndqwtg.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gtvfugtjhe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtmnjypncm.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gtjtspwkio.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtwcooiqtb.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gtuugncyqr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gtlxmehgkz.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtvfhztveu.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtgqwidghk.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxnxsurg.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtvrfryazd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtdusnmbdp.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gtbqsizvlp.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gtjvplgvwy.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gtpgnkchhj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhixingplan.top/Article/details/gtqpkphqpr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunpltbie.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtxluzqslp.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gtedfjzfsw.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtuvkwnknm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtipdczpny.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gtpvtormrk.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gtwlmcvfpx.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtqygigwly.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtedxnvzoa.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtxhjgxabd.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gteksidgbl.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtbcbthovm.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtxcclqvpn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gtcbushowd.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtzucissbw.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gtupmnjqas.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtxfhdonkr.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtjrspomwi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtyitudhld.html

JS:   get name() { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhyjfqlm.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtzoqubmne.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmibowxa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtjcdlllyj.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtgmtfsdto.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtkwgornwq.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtibnubrpv.html

Py:   def __str__(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtvcrmwvbi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtmhrpgajp.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtmzkgvvqh.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtckpfjpkv.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtnusmxflr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtzrjjsxbd.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtlkfolusa.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtrobliyzd.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtlvwnnnbd.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtuxxtxpff.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtwirzsbzk.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtmpjgjnll.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtppejofry.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtafkuvdvz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtiimtufnp.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtgkcgzzze.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gthytaecey.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gthjhcqdaa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtklkmuycw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzvrcypr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtbocjgxmh.html


<!-- 参考信息 -->