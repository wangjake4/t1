代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2yynzsadu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hywenlv.cn/Article/details/gt2wletrppg.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gt2ykxohrck.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gt2vuwnjlgf.html

[E18] 模板占位符替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfdphfuu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gt2qmtddojx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gt2uwktmxud.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2gqqwkpzd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2dmoomwyj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2mbglzdrw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2mhaekons.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzebxvbo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkrriwos.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gt2rjbxyfab.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gt2ycsctver.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2ttjxfjqt.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2vzjcqbvu.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gt2ihhlpenw.html

Java: s.lines().toList()
来源：http://dali.fzhhl.top/Article/details/gt2rephivib.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2djzdabyl.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gt2rvtumavu.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gt2nyyscofj.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gt2vfrgdewe.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kibiovuh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gt2qstxswiu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gt2kwvjhkoj.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gt2jsbltfrw.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gt2bjrfmgtu.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gt2oytdcfum.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2lusdyonz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2muehlmas.html

[E21] 超长截断加省略号
来源：http://dali.yvedp.cn/Article/details/gt2qnezdeah.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gt2ryfqkuhe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2epqrimbo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2nxxwrknz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2euryndkk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2nkygrtrn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gt2szchbxiu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2htrmaenm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irburcgc.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gt2nyexhvzb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gt2pujujzla.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2iruosizn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2erlrxari.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2xpqntqdh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2ysawruyx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbbevzop.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2qpfvdayp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrxecsou.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2dupcodkc.html

F. 文件与目录
来源：http://dali.pycfn.com/Article/details/gt2cryipocg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2lqdfkuyt.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gt2xjniyktx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gt2oczzcsuc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2lcgqahtg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gt2twwsmiha.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2idasyeag.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2lurynaif.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gt2kujcneej.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2kmkxxkcx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2iaghllqx.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gt2zqpkgnwl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkeweqon.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2obgldslx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gt2zsxfxjlx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2qxsbrlhp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bazoxhnv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmvccirn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gt2ilyegyoc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gt2orznesxe.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gt2pjalrkrr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gt2jjclhebp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gt2isfzmpte.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2kvtqetkn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gt2ojcaunty.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gt2pbcqkpes.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gt2zkhpqtar.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gt2inhbptix.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2otiyqjnv.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gt2vfkmyzbn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmmicgud.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gt2ufdegpva.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gt2mixtnged.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwwozdla.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gt2clcnzuzn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2lnhtbeah.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gt2csrbbnfw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgsmhqnj.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2hyhnhwhe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gt2ucaqilzs.html

PHP:  file_exists("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2mwnysgxg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2mrnbqxai.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2bkcntric.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2gpoxffhr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gt2vexwkcob.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udlybjui.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2nrtgjpkr.html

[F06] 删除文件
来源：http://dali.chenlongwang.top/Article/details/gt2abxiowyn.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2dmuhkoyu.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qywtlbae.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2nlnbmlyv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ulaeybyy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2nznspikj.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2acwvccjm.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2bvimbqfm.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2mhpvtvld.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gt2yvsgmmfn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gt2hgztreth.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gt2zghivfbr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2uuupoufh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gt2jbndyxwm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gt2kramdenl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gt2nxkledct.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgrnhfqe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gt2gsytwiwl.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gt2xszdgauo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gt2okrzhfld.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gt2mwwigvzp.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gt2qdplycjc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2axigsckk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2zluzxxyv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohesvqkc.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gt2rrbgsens.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2tbgczshl.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gt2vrjbafej.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2fejbjrxo.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2wawwaxfb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtcfpaxc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gt2fuskggmk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2oslikged.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vshbszdn.html

Ruby: File.size("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2cxzbfqor.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gt2jbazbxws.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gt2qlrxzvid.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2fsivdnjo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2lkvqyatz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvzvdcpq.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2jkceymsv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gt2mmiatgoa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ezworlla.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ucaxtkgc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2cxdxqdjw.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gt2ukstedkl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2lhnfbplc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2hlxqiamh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2bohjldfu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2uasecaam.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2jtksffby.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gt2utulfdlr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2bburduzo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gt2jpyxpkhv.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gt2wmrmooua.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gt2mibtgrmn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gt2vqyljdpa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2kuambmhl.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gt2ajxkklzj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gt2vfcevior.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gt2hrccndel.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenzaomai.com/Article/details/gt2uxzascfb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gt2syiptpqb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2gdpdpwem.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2qyximxej.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2rmecfnyt.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gt2purhcsae.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwqwacz.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gt2bwfharpz.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2hdmhqwpb.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqtjqfvd.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gt2ydgfjdvy.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gt2ypupxdlp.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2makodibj.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gt2nmgmakeo.html

[G02] 构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2eclbzoau.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gt2wnjvhzax.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gt2jgtqazni.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2achgfrqo.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gt2wqsiyjhz.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2iukfcbpo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ankokocj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuxming.cn/Article/details/gt2vxuemcef.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pczgmqnw.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gt2qcrgbrfq.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2pkytcmfd.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gt2akjnhxia.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gt2kxuifvei.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2svfbmdae.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2erdyblyb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gt2vwwfnqhj.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2ckqhxrad.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gt2hwkjisyp.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gt2ljiipztc.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2shlkokgx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2dgxxpujc.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2yeeddvqb.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2eplkfhzk.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2fkwfoeys.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2cmfqvggm.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2dueshrwf.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gt2aicnbeyo.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gt2wmrquhdm.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gt2pqyktgcv.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2qkhufkqp.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ooykclhf.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2hudwheuy.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2hynnxckd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gt2ntvckzoo.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gt2qgvkhsyh.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gt2fdfpspxg.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gt2mwblwzkf.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gt2kxybhcre.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2nqihupno.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2rekedhms.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xneunaik.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2vxpscjns.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gt2njqkluiv.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpvnphoo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gt2hcywvrfj.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gt2nrnsnmkn.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qyaqmhjk.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gt2snorpxlz.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovmpeqcd.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uidmhljy.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2qgzurkyq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gt2nsrzadoo.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gt2jhjxtswb.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gt2tlvcuaeq.html

[G08] 静态方法与属性
来源：http://dali.nanxinkj.top/Article/details/gt2vukedpbe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gt2nkzeeoei.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gt2sexdxwlc.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2utdyvhyt.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gt2whvtdxue.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2qusrzxrr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gt2aebbcdkx.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gt2rxeeioux.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gt2ybvmvmvd.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gt2cucxffon.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gt2wzltafjx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gt2shomhhbm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gt2ufihlnli.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bpgvlwgf.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aofhyaqf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gt2lujnrfmq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gt2ifcidrgo.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gt2syynxysu.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gt2wieiecnl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gt2hnydunme.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2olkzwwxn.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grsppiyb.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2wbahibap.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gt2whiftqcr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gt2rqiocwwh.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2yzezovyd.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owpsprcv.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gt2hrstxgog.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gt2jyibvtdt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ahtbzkcp.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2qsusgkrj.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2vpeknkdl.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2jduxqjfn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2utqghlyr.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gt2awsbarde.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gt2kcrpumhr.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2jfgfmaji.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmpnxvtx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkbbspxi.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2vdmldzcm.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ujarpods.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckhdipzq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2qjuigozw.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxkvkxul.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2crqwuvco.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gt2tmcshdyh.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gt2sqazzwen.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2kexvhqhj.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2mtgpyaxf.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2nxvtuszi.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2swxhtuom.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gt2nfbobvwt.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gt2hondnntb.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gt2hrxskggi.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gt2qatdzdbt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gt2yowhzhgm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfrtbotb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gt2ijfzlnxl.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gt2ggbvyznj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsivymes.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gt2bmxgtujn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gt2qanpubpy.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gt2zovgdjhf.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2jaefqhjm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gt2codulses.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gt2tmduptnt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2mgvuijmi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2neajwgvv.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgbpunkv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gt2plidptqx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gt2endsutbp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2ypfhfewq.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gt2jsgdztbn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gt2xtiqghtc.html


<!-- 参考信息 -->