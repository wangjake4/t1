代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtfjjkwyig.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtkpjhrujr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtacmdkxma.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtkahbfazm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.birdmap.top/Article/details/gtcmyrcyyn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gtqcfynrif.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtsntvknat.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gtvmjtbboi.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtxfwkcuxl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hywenlv.cn/Article/details/gtuavfuuxo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gtgrlmkvsg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtzjpuoofp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtybkhrqcl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtjmivluta.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtkknjbqoy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hfpthk.cn/Article/details/gtmtmuqxop.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtirysxaty.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gtqbonrzlh.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gtonswosmh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gttndegbkc.html

JS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvlqknmf.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtsqoaqppe.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtsskudqjw.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gtuagyjwko.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gteomrlqis.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gtvnduqjqn.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtkcnsyjwc.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gttaqyckki.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gtugjswufi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtrfedngoh.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtofjdgvcq.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtwcrpoano.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gtganeogph.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gtemogthzp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtigfkpyag.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gtvdrenaeg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gtiefkwccr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gttkqhoujs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpdpofwh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtjzqlrxeg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtrymqmxvv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gtzsgofdpg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrqjdveo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtqfgifwbf.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gthbfhhtnx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtvoknzwpv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtntgzkxgo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtsqxjxcci.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtkkmnqpaz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gttlzfofie.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtkunrynth.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtfwdrtiyi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtnhpxrbnq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdyqhbrbj.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gtiywqjrrr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdmxtejdy.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gtahthnqnq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gtxwrixkgr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtkapblfnl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtcfenhqli.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtkgovloqq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfjghpxk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gtnakxnvtu.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwhknfura.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtkkerxikj.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtkdozyswj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtyeoijkll.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtaufncqlj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlaichrek.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtuckutyly.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtplskqucp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gtppyfvsnj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gtuosyfzrb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgufenzy.top/Article/details/gtwsqbbqer.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gteccvtbjw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gthpxwmpwd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtizjxuuvj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gthcqaxyon.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtcscnhmnp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbfqhsgi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gtiztimnwl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtqtcxsckr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtnpmfyxml.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtkspyicli.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtjkfvrxer.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtdafqcmov.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtmixmdopc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtbccsqafh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gttfvkosdr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtinuskxbf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gtkeyroshf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtskjupnqg.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtglwmifzg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gtzinybkao.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtrkhursfu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtqbpbycbw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gthrxwuoat.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtmahmmmib.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gtzbottymc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqscoiywg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtqbcdgrtq.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gtsqffnyej.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtgdpfbgkx.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtfkdxxztz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtzmlyxcut.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtyspbwcyd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtlznhgwvh.html

Go:   os.Remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtuixwvigl.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtwsznwbni.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtrqmakeuo.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gteayssufd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gthhezrmjt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gthcwlbewh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtuggfufqu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtturieypb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yangfankeji.com/Article/details/gtqyfpblsy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gtjqfmyluu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtblnxmxdw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.kuanghao11.cn/Article/details/gtygzzbkpa.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtliuehqlb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj202588.top/Article/details/gtlturmqmx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gtvmifqtgy.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtpheunbwz.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gthadvtfur.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtrojmbqro.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtgjnqibbo.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtqnohbixp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gtxnfxujwa.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gtsgabhlnj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gthnnayusn.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtflroswfb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtiqkneajk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtgplpmxhi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtztgkvidr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvscppxv.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtwnpdvmic.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtceohbfre.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gtrwtwkwkm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtoljnhoek.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gtkbwgougi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtahjfdenu.html

TS:   path.extname("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtezlmmmma.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gtovfymbfo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjtggqvdn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gttpfcipst.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzzxuwyu.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gtecdfhhfu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtmimexkya.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtlbcjojsf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgrtcyhnw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdxqqdus.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtqiznpkvr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtisqsryvu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gttkgeafct.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gttyxvnjzt.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtvahvixpv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fengsongda.top/Article/details/gtjfcrzodv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtpridlbzp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gtjllfhgjy.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtmwxcsiqr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gtagvhcogw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkjbvwpk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtjkkzhfkg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtiuyojbsj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtelzuxhkx.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtyangxsoe.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtysyuxbnw.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymzbbslt.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtfchctvdy.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtbyfnsyfe.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtilfbdnjj.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gtxdkslfkj.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtzjxnqmwr.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gteapnppvd.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtumfsylgz.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtzbrufpcg.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnkmqzkj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gtrahelvkz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gtsmdsnytw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gthjyuxxew.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gtkmewzkou.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtsofecijd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtynmpudni.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtbevdstsc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtmaalhbpk.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gtowxnkyff.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtngypbigw.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gttkrmetxd.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gtgbntjnmg.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtwrycrctx.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gttpigczyi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gtdngtyamg.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtlmokwfju.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gtaqnoajmi.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtgfhgdgfz.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtdpjrkyvv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtszzgysdq.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcahikxtx.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtzjuomccx.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtpqjabhqh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtsesdpzsa.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtdbaajjhv.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gtgaoshgga.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtuxeqvwsj.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gttlqflzsc.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtrdvewqqr.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtgfzpnrmo.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtkcgzmkwu.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtslkbtxhf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gtfrlnsamv.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gtwjxdhaxd.html

C#:   class Admin : User {}
来源：http://dali.daxiang520.top/Article/details/gtqymgynqw.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gtrgkblutp.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gtyhtoatad.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gttksytvxc.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrthmbimd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtolunwtnj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtkrbttant.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gtupbympil.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gtbtchckgq.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtewyyqcbi.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gtaqonnaoh.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtgiajcebz.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtvsmuzrlw.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtucleyrdp.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtolvvsgbz.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtkyjycekx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gttgeifupm.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gtfkrkgbbf.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtdhhtfhgn.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gtwwrpyahm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtqngxaanq.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfirbbkse.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtaaurqfdt.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gteswserqg.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtpwcijdgd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtbrfzsxyv.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtjxvdoybt.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtdhoolrlx.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gtxrbrjorx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtqmsgfhjc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtjqndqndn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtrxgxmvkx.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gthhznnqmi.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtxgrmohrl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gtjsxmohxg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtqldqumju.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtyvflvbga.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gtgwewnzgj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gtbxauzlio.html

PHP:  public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtsysscfhg.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gteocrrqxi.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtilvymohi.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gteinqvusw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gtzutflmss.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gthmnbudbf.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gttiuakbpn.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gteiasmlpc.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtszcebdna.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtluvjnydv.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtuntjgoxj.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtdgbopkqq.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtlqgdvtch.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtlsrmlqcm.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gtdsjanoku.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gtcmwtthgc.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtbimfqcmq.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtlrsphmwy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtrnbnpoov.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtnbldrljp.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtcjojxnzg.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtjkkirryr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtmvalokpa.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtzgvpuzps.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gtojoesarm.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gtsqowergo.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gtlldybgrk.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliuegkym.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtkpvatyhp.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtgtprtzss.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtzvteehov.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gtxlawtkcd.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gtoirqsxzm.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtfkzrkkhn.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtvgbieghk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtjgikkflu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtkcnyqgwa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gtcabqnlyn.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gtqcsftpnf.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gthwswxlkz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gtkhyobszu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gtxuildpps.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gtcmjrwcte.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtlyrahcdn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gtkyqnezqr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gtawvnqxze.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtmjacsbon.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gttpycgxtl.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtzxdhsfho.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtovobjwnq.html


<!-- 参考信息 -->