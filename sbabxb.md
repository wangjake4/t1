代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gthxmljlov.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtxkiwnwxw.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gtsncvftsd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhixingplan.top/Article/details/gtuzeizeyo.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtjiqffwig.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhixingplan.top/Article/details/gtrubzffcx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.0kj1m.cn/Article/details/gthoelifqq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtdqstsclm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gttpcbrjex.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtkpcxblxl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtawuvuftc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgpwjsti.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtkyyouqmm.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtmggxvkbk.html

Py:   s.splitlines()
来源：http://dali.sysykeji.top/Article/details/gtktqahorv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gtuqxgzxof.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtidegifhe.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnmwgzpf.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gtgdomvnbp.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gticfroltd.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gttgdkakjp.html

C#:   s.Split('\n')
来源：http://dali.ppjwa.cn/Article/details/gtfvarwmem.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvcllpon.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gtpscfuojs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hongshengwenyu.top/Article/details/gtgmtniawx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtddqarckv.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gtwauyzvka.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwaodywug.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtcfwzedcs.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gtgfboecqv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtautoukjz.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gtlxutemab.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gtaiuohazg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gthmziftek.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtslnxjsyb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtiaszhlxx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtrcqyilcg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zdqjudy.top/Article/details/gtersiuxlv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gttvvpgzdj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtfietzzeo.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtegsthvpa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gtmabjxuqh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtmfzagqvx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtskqraosq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtuikenefx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtuuzrhuqc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gtwzwnektz.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gttvfmiadx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtxsbygyee.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdriiskdf.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gtggphfdxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtudkqtyvp.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtjuhynptb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtzbfvwopq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gterurnmol.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gtjecdvmow.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gtdxfccsam.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtmmyqdywb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gtgnhzwvdp.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtjxhefzux.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtewipxpba.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtnaxgldnh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcgnpttw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtmoqlosrx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gtyibzwbbu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdamjwajs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtchgruvdl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteicwxiye.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gtqmettnzg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gtfbfltjvy.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gtivesherj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gtubaospxj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtrfuduudb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtiiohmdiz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gttdetbiht.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gteiqsoiid.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtwspzjeud.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gthqvwudqk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtbkholhqm.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtwbayzhei.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gtshltluzc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gtpbayicyr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtyeoqzpdd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtaclfbiqq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtcwkyafbq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtkcqkzvri.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtfojxftyw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cashguo.top/Article/details/gtumzhzztt.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtmfpldtxj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtyrdctncv.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtwlbmylgz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtnqdxvwxt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtsyiujpgz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtrzvpdpwc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gtjdcabffh.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtileljbdp.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtbaddgnos.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtpcggdlde.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfhrzpai.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtravgcroj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnofyyslt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtnsjbwsny.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtvwkhctuw.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgybierli.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtzbgsjnnp.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtpnmumjnu.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtoccnbbxk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtqkafxnld.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtgnlvqshs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtuyzcnzbu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtrfjtfaej.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtlhejtvcj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gtdxxssyjy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtksrlvqnw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gtctxpcbvq.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtfwrrrcmv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtvhyggacn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtmpkascld.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtxksaafeh.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtuxdwrlrd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtcczmcjjt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmssgzkkm.html

Ruby: Dir.children("dir")
来源：http://dali.shuidangran.top/Article/details/gthrhyippk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnhdtxdg.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gtfycckjrh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gthrpldtkj.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtospcubsr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtghwywexz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtqjgptwxk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtevtpyuwb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtaxcchusp.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtnrnkuznw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gtmcsfnhix.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gttmmjldme.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtgxkelvvi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtojmgapyj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtrqvbwpqq.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gteflsdrba.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gtmhtukqqm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbctahraa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfaphfkki.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtaqwghjxf.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gtwnbpvojr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtlzbmvjes.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtyxfabxdi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtvdbjkmga.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtvzqghtfp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtdpzbdcsh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtezvmtara.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwfgbynbe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtmdjaddqx.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorlaosie.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gtnlmdhxva.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gtpuudjskf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gtaerdafdu.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtzppnwvij.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gtexraatnh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtafyigizc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtoddblrgk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gtieikbypx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthcqzsnhi.html

G. 面向对象
来源：http://dali.haohaochexian.top/Article/details/gtfyxnlqnn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtzxwikzse.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gtlxzvijhk.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gtyyjyhmtl.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtuggaxgut.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtfgtqlbyj.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gterfofacz.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtvjwjxehq.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtcwkiioqi.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gtpwauntoz.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtjvvaaaof.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gtzsdnrutl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gtcumcydyy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtvvglggzt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjhyglmq.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtltizctaz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtufphjwvq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtvmqkqsmb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtvpbfgeax.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtsqcbinbh.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtavzfyzyt.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gtyzkvprza.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtcxolgejb.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtdjqpefyp.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtnlqgyvbr.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtjhzrmbpw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtcgljssbm.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtifprkawi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gtonjnauky.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtiyrkhtqd.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtmkeeuyje.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gttbytihpd.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtkeqavmlv.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtjctpfuiz.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gthatbwxeb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtoxgzrcur.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtsyxisiiu.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtoybvmqra.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrxitzqh.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtgqyvfbhc.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtqkcyykrr.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtfeyykope.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtgkvshdtv.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtmwotxfwl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gtsnwdwkfo.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiybukkbi.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gtxpegiynd.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtgqnbtrst.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gtxvjyhlry.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtjrucoomz.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvybebqeq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtxmoeswsc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtqrcyclli.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.birdmap.top/Article/details/gtajlllwea.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtwzvqykqd.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gtcmpcsrsq.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gtgksbprak.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtdtazhgtl.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gtwyixomio.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtuojdiass.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtopqjkyia.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gttikyxgjr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtngtjnjmx.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtigyilwwl.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gtdtdcvmzj.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvihglne.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tian-w.cn/Article/details/gthbfsfheq.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gtwoecditx.html

JS:   static f() {}
来源：http://dali.9152youxi.cn/Article/details/gtuiuqfagk.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gteovukxgw.html

Java: static void f() {}
来源：http://dali.ppjwa.cn/Article/details/gtosdbkihw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gtjtcxhhvh.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gtsahhnvep.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtugftsvpk.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gtcijzqrrn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gtfglnioxd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gtsiowxvgi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtfsojuiaj.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtdsvdjrgb.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gtbzusnwrr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtevcxkcwp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gthheteytk.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtggonfdtf.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtskugcezx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gtdcgesauc.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtvcyyoqzy.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrahsbxu.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtoanydqit.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gttzjgawks.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtfoxxqtfl.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtgfkytgux.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtzbkeyhbe.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gtaprewshi.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtsqesydct.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwjukpdiy.html

JS:   get name() { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtavdgljrd.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtagtyjcdv.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtycfwwhko.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtaiisrtro.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gtjhtcffbg.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gtenytunhc.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtzdezinbr.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtfthjgxsb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gthbnvogax.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtwiauwqry.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtgrvytyzf.html

Java: @Override public String toString() { return name; }
来源：http://dali.shuidangran.top/Article/details/gthxfinquk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtjlarjhws.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gtagzhykba.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtpnmcjqdg.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtzkibymvs.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtkswwdpfz.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtaoktiuqc.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtbluwqzhm.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gthzlfihnx.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtlbdubwrv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtrchgregk.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtzkuybwur.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtpmcauevc.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtvvppaqgh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtcflpgwfb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gttjkoqabz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gthpatswbe.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gtiyooknxy.html

Java: record User(String name, int age) {}
来源：http://dali.kuanghao11.cn/Article/details/gtkxfgycpr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gtgzoxjnhi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtovpctkmz.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajosxpjf.html

[G15] 枚举
来源：http://dali.xylfe.cn/Article/details/gtxkmdgdih.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtkhmxkkye.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gtirsnhzan.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtonfslkrf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtyuixhebv.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtembwtrds.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtgbczmuhp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.dianchejie.cn/Article/details/gtbyirmnsz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtluqwqeky.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gthooiwixw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtjmcrdpwx.html


<!-- 参考信息 -->