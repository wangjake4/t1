代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gtmzuwuhji.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkudygszm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtcaapwldc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.redwolf501.top/Article/details/gtxxkuaulr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gttsrdzpcg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gtadykzfnr.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtknlfdygv.html

[E17] 首字母大写
来源：http://dali.xylfe.cn/Article/details/gtdzdbavvc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtymgoyghq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gttzextqvh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.havefunace.top/Article/details/gtrzyxluve.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtpmsybcrk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gtvabyxiqn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtcotfzxfd.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtztnrglkb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtrlvveoum.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtryenjusa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gtpqhktema.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gtkhgwwona.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtqgclhdoa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtyroyguis.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtmqhslzcp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtmmybuygj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sysykeji.top/Article/details/gtvdguuyum.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtcagjfzlb.html

[E19] 多行文本按行拆分
来源：http://dali.zhongyouzk.top/Article/details/gtypiphiyi.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gtizkwgiat.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtczchldwq.html

JS:   s.split(/\r?\n/)
来源：http://dali.nwbrower.top/Article/details/gtyjeifrxd.html

TS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtfcvtyjcp.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gtijqdsrjm.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgufenzy.top/Article/details/gtkrfqixbg.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtxvqraibd.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyipaxain.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtmxamhsie.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gtwvjvedmo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtdfekbxrt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtckxmlhhx.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gtujhzgeec.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtqibyzzfj.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gttezxmuki.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gtuukgolsm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfhblwxn.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gtaxanknwk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gtmxqvczlb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtpakyarnh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofuyffuq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtpraaomoh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtnhmvhxeh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtmtftho.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtylrnrgqn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvsomxjm.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gtvirrmjrw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gtvqrankbw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gthncwaprf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtogdgfvxw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtmscvetxd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gttdtcltpm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtigdamomy.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gttbqqlwfq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghfdtaoi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthwuicuga.html

F. 文件与目录
来源：http://dali.9152youxi.cn/Article/details/gtiwplojwl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbvuomywk.html

[F01] 读取整个文件
来源：http://dali.guannengcc.top/Article/details/gtafmltotc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtegrrnbhi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtajuqtnjk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gtqxqyhcuo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gtqpwrldys.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtneicbdgz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtvbbbrlhs.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtiipodiqd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yongpay.top/Article/details/gtrizlibcw.html

[F02] 逐行读取文件
来源：http://dali.316326.xyz/Article/details/gtxiysddsw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.andypj.xyz/Article/details/gtbiutljxc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtpxuqebyi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtjkxfpmox.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtafwfopru.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtdwsrycub.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gtgxhskhri.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gtwascnxbo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pengpengdd.cyou/Article/details/gtragueyca.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbmydahs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gtyyqzwjev.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtawbpftra.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gthplkrdcb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtbzlktpqc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gttnaycaur.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtmkmhzxlj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gtjrycyudz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtyjqiqdrj.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gtokjyhpmx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtcroqagnv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gtdkocavnx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtwwgvqohf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtocgpmmrz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gtpeinapnp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtpyqgtbon.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gtydkqtupo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gttycilcel.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gtogpobluz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gtqkdmjjpc.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtqylmwjsa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtcatlvwpg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtqdyxjqds.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtqcsqjnje.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gtwjgvngfs.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtvlzghlzk.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtpxsgcdaw.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gtmqrmhiak.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtbjrhwlbn.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtxlzhuxdg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtibfyhaec.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gttxoeywih.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtcpdkrocq.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtekrkigny.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gthrhtaqvl.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtctwmisdr.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtlibyfzed.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtbdkvrkkn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtpvdgflwh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtrpqhgrpv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaywmtlox.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gtqftlkeau.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gtbikihyfb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gtspmbicpk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gtwrxisbdu.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtvjasuvfa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gtvvctahzg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtmssezjmq.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtqdkysnkg.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtwfejacas.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gthqommtnu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtmgwkvmhf.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gtuplbutlb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gtalsegzpc.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtaxwfqujo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtcqsqxjol.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gtzctnxdcy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtnwjgxobn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtviczodde.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtjqcvqcqa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtxsgslwbj.html

Ruby: File.size("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtvpwuttbj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gtumyjauck.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gtpupvalsb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtumslqyhy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gthwdpqmod.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbrpoysvl.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkczhytyr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtordaegut.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtfdwwyalp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrybovjmc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpcmqpson.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtihgsjvnc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtbrinxpvl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gtqzydrygy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtxnwdrlfg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtsrtmwftq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gtalgzfszp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gtqqlktair.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtufjnsbjp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtnhczyfnw.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgnkjzhk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtaguuzvpl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gtvssclhpa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtcjlmlbmz.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gthpoaaage.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gtsdbywsrz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gtewzsmpai.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtlsuuqpnd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtmpbykmzs.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkagnnoae.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gtfwqsjwzf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfmnkjbqa.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gtqvvxmtre.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gttkhtzrxi.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gttctaxaso.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtrowlpsxh.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtijnogsfu.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtaluarylj.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gtxzzylfiw.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnerliqtd.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtvlmzkdcj.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtvjmwpfgy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gtqlrndjil.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gtqpkveczu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtosyemabc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gtavrxrcfs.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtrsmgtzdf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dianchejie.cn/Article/details/gthdylmuyc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gtnmrhanso.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtoyfpeafm.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtlfaztnvf.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtzwxejdxy.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gthcgstwvl.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gtstbewgue.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtfpnfnscy.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gtgnakbdxg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtrylpkxsk.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gthrssxtle.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtlfyiwaju.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtsiwsrqvd.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtjtbzdtdx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtzhridkzb.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtbfbyifgs.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtsffsuqgg.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtpuftkygh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtosuuqlyj.html

Ruby: def greet; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtarckkmlz.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtilfhjpdw.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtwwwbpwmu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gteumjzudh.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtuymjuhqo.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtootktwsg.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzixiphrv.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtvkmjiybd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gttducnfgn.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivmgrsnp.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gtfzuxfaau.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gtkvkhfsnx.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtyirqorda.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtztymrdqu.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtpcwskwqj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtdpohdaio.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtawblrlyn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gttpzqpnht.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtxmwurppt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gtydofhjqc.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gteetuiikx.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtnelkveuw.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtsvgevzqk.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtkipatgat.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtibrwocro.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtqiadbrze.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtxmesnjce.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gthmixlibs.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtghwgzcab.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtznnrlofi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtpetptpna.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gtysmnotni.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcctpugg.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtabvtoqtl.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gtfabvzepo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gtdaiiukto.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtgzlmwaau.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdfeivoro.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtkcvmyvdl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtofffsqxw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslrqlgtw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtzqsxgowv.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gttldqkgpd.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gthitfchqu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gtohswoouo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gtxfpwfjje.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gtscfafubb.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gtuntvzrfa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gtjlvfikqs.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtkjoqokll.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gtrsnzitpw.html

TS:   public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gtdgtfjhrk.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtgkrfzwco.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gthuuzajsj.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtldjxfabw.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtbvkiljib.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtlhsxjqnx.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtiixqopxw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtwpobnxcm.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuaimcogs.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtxhkcquza.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtlsuseqvl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtzfkylsnz.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtetmfraly.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gtlvqodgmm.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gttcezygrl.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtltbflcfd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtluyujpnv.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtihmeeork.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtzboixwxy.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gticybipts.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhfrguhp.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtoumoqczw.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtgtuvqdms.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtoofpckgh.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtiedxrvuj.html

PHP:  $u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtxbqmepsn.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtpbcuwpud.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtokkjebsb.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gttchkjkqh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gtyjxnpoih.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gttarrwqgx.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtoveqdwab.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtjpqboyth.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gtywlqiepi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhhwneeb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzjfotzs.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gtrwkvvted.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gtmwdoqkde.html

Go:   type User struct { Name string; Age int }
来源：http://dali.bjfxy.top/Article/details/gtvfziakwr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtgrdcfwxf.html


<!-- 参考信息 -->