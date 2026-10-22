代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtilfkmcqd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gtewefjlji.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtxgxubimm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtfhonnpyh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zdqjudy.top/Article/details/gtgdxzsrki.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gtsaqdqkxt.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gtjjhmmtxn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gtrbycpecy.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtgsqxodwp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gtcasvapwy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtwdwkejzx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtxrvnveji.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gthvfwogfm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtgwiwymcb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtqkayhsjq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gtimmzxjbp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gtctkdtbqz.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gtzosgkqjf.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtveurhtbr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtbmwgxjgh.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtmkdxmzkg.html

TS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtwwajgybn.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gtfpqzcvmx.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gtawsgwkum.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gtaldodcrw.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gtcpgqlimp.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gttrcwtzqz.html

Py:   if not s:
来源：http://dali.iojbl.cn/Article/details/gtojuwmyzj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgfzy.top/Article/details/gttbrbkaen.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gttlajgeek.html

TS:   if (s === "") {}
来源：http://dali.jqgufenzy.top/Article/details/gtnghkvcid.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtqmkcemww.html

Go:   if s == "" {}
来源：http://dali.0kj1m.cn/Article/details/gtukcvmboz.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gtvoepajkc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gtnuqndmsr.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtppqebdxc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gtqbviigje.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtqmkjwait.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtwtirioew.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtkyfmfeml.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtxdihampc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yangfankeji.com/Article/details/gtpxrhutve.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtjmiypuxc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtczezjbum.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gtknwammgz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gtnutdejbr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gthbvsvssk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtasnkzfdr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtgjwbfqck.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdngfcje.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gttbddfpxp.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gtkdjhoqrd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gtofzucett.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtksqnojcn.html

F. 文件与目录
来源：http://dali.jlsjyb.cn/Article/details/gtzgnrvgxb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqjymxayk.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtqslnfpgj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gtvekljlgf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtudbrgbkd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowzgxtgw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtqzbzqzec.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtxkqgseht.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtxobvxjrc.html

Ruby: File.read("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtlfbnzaad.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtknfgplto.html

[F02] 逐行读取文件
来源：http://dali.fzhhl.top/Article/details/gtirohkiru.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtmqzmawte.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtlqeujjnn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gtbglkryip.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtadxqelof.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtaieqxhpi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gtxubunzzc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gogol.net.cn/Article/details/gtlranbben.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gtewhanlti.html

[F03] 写入文件（覆盖）
来源：http://dali.wangshuangyany.cn/Article/details/gtopeamina.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gtljoapqae.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtrynnzmar.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtrjhfdfpt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtgenxsjuj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtnmhexvzu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gtjoywmxbj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjhpumjq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtudcditub.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gtxilpzlpv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtnuemqjxn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gtvzjrpsny.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtbmahnaag.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtuttgllst.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gtofuukjva.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtqqmqtlsf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtzbubqlcx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gtgxbtzked.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtjunbnqfc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtsztkyecl.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gttltpcwof.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtbyosbvsj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtfxxyhoho.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtsffybfkb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gtlykfystg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtemxufclx.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtgsijzggv.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gtjkcwhces.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtuwcgpddk.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtszhojhyr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtkqeoviks.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtnqknsrjh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtblnjotdm.html

Go:   os.Remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtpmcajovc.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtkzkighwe.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnhwceqz.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsavkhpjp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gtskwcmcwu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dianchejie.cn/Article/details/gtugmpizou.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtahlhylpy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtfnmtwfkc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtpqqwuehz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gtdhhcjmrg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gtwhzsdeky.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtuncjgbgc.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gtkdpbyukr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aizwys.cn/Article/details/gtgcliyvdv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtwlztrolw.html

JS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtuvehhkow.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtkkcjgdhl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvipxqfer.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtrynqyfau.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gtpjtyyfqr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtwahxxcxb.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gtojefzvio.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtlsjomyne.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtnmeuvren.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gttffeycmx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtjfetfhum.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtwpfsenwz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtnudszdhq.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtuuzbtumf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwsicvlk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtlixprakd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtaswrbcag.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtifvtsxci.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtbvxdxoac.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtdmjechhl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gtvaawaczv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtfslsgdmd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtiescbeox.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtaxjdtkzu.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtwdshkted.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtoniwedal.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtngpveizn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtimfkosrd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtvssesgdn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtgyzdrski.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gtsdyqmsye.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtldmzjpvm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtqcywinxi.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtohmaranj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtvfwvnzfv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gteboytecp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gttwbxlpxp.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtlnqevhkb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtrzmzrusm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gtmykgzqtb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmhwtnzo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtgdsjdtze.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmulquorv.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gtxzvgnbnt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlohvkxkg.html

[G01] 定义类
来源：http://dali.gaohongyu789.top/Article/details/gtttenabjf.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtqocogbew.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtyuuyihvx.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gttrowbguz.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtynvoqsoe.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gthzqrkqop.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtxqcprcju.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gtlzearkhp.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtrvdjmnzp.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gtjgajpaie.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hysaishi.cn/Article/details/gtzuhgttou.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gteajvhtzc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtzqlerjqn.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gttcdpqqvo.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtasoilupw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gtnrzzihbl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gtvaupyvyv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtvcwagunk.html

[G03] 实例属性
来源：http://dali.jinqigfzy.top/Article/details/gtodrzrqya.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtmlfyfmra.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtffbmsedr.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtiuvcoooo.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtvdocnrar.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gtzyvwdsge.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gtkpredrnk.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtutsnjupz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtpsfmfynd.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gtluxwmzxt.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtevylnvns.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjsgtswg.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtnxpbdbbn.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpufhjgub.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gttzqanzza.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtyfvvjfrg.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gtftxefrko.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtpgtsbkri.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtlnnytdow.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxgnzwsx.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtefntzkuh.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gttjzmsltf.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtyiecexlq.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtbwjjgezy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gturihjqer.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gtcivuadvt.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gtadmijeuv.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gtamlmiksb.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtyssdcavt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtwhnkppcj.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtwpweelqa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtxmnvdoqh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtzebipysx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtmzamjhmi.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtqejdynfs.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gtkbfgobfm.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtpdzzfnyt.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtcjppefsd.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gttzwzoptb.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtcygfakrg.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtnndfdbbu.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtrolqqyne.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gthwdfrrlx.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtevjvsmsu.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gtilrekiat.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtqtyhdyoo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtksqxdcnx.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtshodjvxr.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gtbbgnihos.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gtttpknqkl.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtvgylfmhx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gtibycncmi.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtxfehrouq.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtmevuyipn.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gtkvmdkgsb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtbukummef.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gtiraqnnqu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gteinupiyg.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gttsdpztap.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtxnbcaoag.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtedvmhdjd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtlpwdshmf.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgadamigh.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsrxvenr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gtcnznxjoi.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtwtdrnily.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gtccixkwbd.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtfosownwk.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtpdhvqbrf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtoukgbdbl.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhoyaftw.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gtkiwshbfq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtuawnbccj.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gthmzeuxxm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtahomdmup.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxejgoogx.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtjzdjkcro.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtbufdhpmq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtuqhakyrq.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gtncznyxax.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtsrzginqv.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gtztvnnybz.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtkpaexgdv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtsdwsxuir.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtddcpxely.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtldoeibyr.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteeohhgel.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gthzsghcqi.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtndzfdpdb.html

C#:   public override string ToString() => Name;
来源：http://dali.dianchejie.cn/Article/details/gtdgunwokg.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtvrugahce.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gtjclejufc.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gtkoqjueal.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhmjfmeh.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtpjapygzk.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtckbuqv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gtjkfogqqj.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoedpbgo.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtzhjhtgfr.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfgtsjvz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.mhx1999.top/Article/details/gtefcwzlkc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gttqxuphhu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gtfnxlpnpn.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258888.top/Article/details/gtxhthivyv.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtebdrykjw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gtipgpjtma.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtgrixhtqu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gtqbadnedc.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gtlsoptfei.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gtyrnualce.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtwivxyzzq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hammf.cn/Article/details/gtcpbhoaql.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtwkmeqttk.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gtxjntvlej.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtyqoxtrdu.html


<!-- 参考信息 -->