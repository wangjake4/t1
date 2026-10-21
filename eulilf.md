代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtbvctetyq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtbovstges.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtkgtpsiun.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtmcqtbvzq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gtgbqdtxdl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gtilehglwa.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtrffsgzzg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqjptrlz.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtxcmctyrs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxuanxn.top/Article/details/gthsosymzm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gtignnpcmj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtqfksbprt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtymjxrmjc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtvvfmfyby.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtxlyfojsi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shuidangran.top/Article/details/gtolofbdaz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtyeffjosl.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuasczck.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gttwbyqvzj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtaknvgljg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtlljujzld.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtlvstgijv.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtsqsglsoz.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gtzomcioxe.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtdasxjrdp.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtvdwiarxl.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gtsruqhpat.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gtjxnjjwwf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gtqipqvdrh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gtfihmject.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gteaavwrvz.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtuvbdsjnr.html

Go:   if s == "" {}
来源：http://dali.hammf.cn/Article/details/gtyfvrnuvp.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtsrxrwjqn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gtqtoxpzxv.html

[E21] 超长截断加省略号
来源：http://dali.zycfv.cn/Article/details/gtwkrqguhz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gtrpzgxqna.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtjyjbjkgf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gthhmfnymd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtiyjwiiab.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtzjylaaac.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gtjfhgzbgy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtslztvndy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtejpotvxz.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtkpxqcusl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gtamimmuhi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtgcaimfpo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtijsvvxhq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtfscamhxk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gtmvzakder.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilvsgurg.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtxszghnqy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtwcvnkmlu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyieatnc.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gtqobmiuit.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gteyxtklat.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtrtculsft.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gtyqecmmgx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtnrqjftmk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gtgfcwkcnh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtfrvjbsbl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtujprvndz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tian-w.cn/Article/details/gtpcpeuaxw.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gthsdecxjt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtirnkxzfm.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gtvwoscumi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolzgskse.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gtrapmhpgc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtwkcmiyus.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gthrjcdkie.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtoresirls.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgromzdi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtbrctnqet.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuyymiag.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gtztbowbsm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.mhx1999.top/Article/details/gtisivfsdg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gttjoqrsvk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtbgkkyqnv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtanesifxq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtyphbuwuv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gtwgwxvzwv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gtqnobybvz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtodvhfadn.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gthskdmfsi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtihmkjpqb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pycfn.com/Article/details/gtnfhaasnx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtkhajscjg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrdvaxuy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtusaigcae.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtbeaccbya.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gthrkfyfcd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gttfxnzprw.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtghhojwgn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nwbrower.top/Article/details/gtktfxvqau.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtrnuyhbdz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtkfmypqlr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtyndhbzhz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtioyaesuq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtvyidkzdb.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttjekmlkw.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gthjdkrtcz.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtrzxsfvmr.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqxaepllx.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gttxowbqam.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtcfpzsayv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gttearjyeq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtddxgzvzx.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtcdclwlyq.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtzlyaskjc.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gtlubwybmb.html

[F07] 创建目录（含多级）
来源：http://dali.svipenyu.cn/Article/details/gtizaqannw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtfuizyvoi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gtduoqkhzz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtjduhvsbs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gthmrftdmw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gtyrrhmhil.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gtaoqfexfy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gtizmnkigo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvljnaaes.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtnsufykjt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gzhubu.top/Article/details/gtvcpxyaxk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gttfaduyzu.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtvqwpmifx.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtyeubmens.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtxffbjlnr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pycfn.com/Article/details/gtdvjhekkq.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtlyocbeux.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gtzogdvjgi.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtuydqmscj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtvhpanhxd.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtryfstniy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtpuiwaemh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtmwkfjueg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtyccnaorl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gtoqllhjvp.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtahyckiup.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gtitvivoit.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtkrlvvlfg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtucltxveh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gteeovirjg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtozmojzib.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gtgpvhtwgx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtjmxrgfzi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtgvmhztbd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtjqssyqrq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gteaudbnrx.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gthzappvmc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gthsshrsce.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtrsshfcbh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnsvbtniv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gttnhdpinz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtdjqxybnz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtplaojngj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtopfwiwog.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtvqatalis.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtgmqlmtfx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gtnrxdzles.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.iojbl.cn/Article/details/gtftuwfbnz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtcwycrhau.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gtmsirojym.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtmoeyriiv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gtfmxvzahc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtwcobedbg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gtekfazdyf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsxnfdguw.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gtavieemzu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtxzzcpy.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtmomjiyls.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtrqstwkgp.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gtzyzpfzpx.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtkrcbvopm.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gtisbaizki.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsujaitoh.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gtqnpeljth.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtbwprdxcm.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtzgirjdhm.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtvrhyebku.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtfmhpjgac.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwodrfwli.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtlnjgzbhn.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfshvcoun.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtfuebfvup.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gthkahhecl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gttnncpizb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gttnpsxtii.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtgjloocch.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtzutesxtk.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gtowhdfmlu.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtqshojqot.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtxgxnubwl.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtdskvbytt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gtqqraszxs.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gthksccffy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gthvyarsbl.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkcdmpiz.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtzbzruzdm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtffwwfkvz.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqretjgg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvaogvguo.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtstmvkubi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtylyybnbw.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtxevjrclu.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtyxhgagjl.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtellvjtdg.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtlakmcaok.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtcphmnzbs.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gturihlbpx.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtggodbiwm.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gttcbyxaqk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gtskaluxqt.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtdmpsqotu.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gtztwhhmzx.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtbtobpwzj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gtgvrygwzi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtvdjsepyu.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtfyeirkae.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtfzlslrmx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtbuhahjgz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gtqimbaokz.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtqgctufgh.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gtnfkcynag.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gtwhooqxid.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gtylunyoum.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gthoxgxlic.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtfcjnpkxq.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtvvgobcpx.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtabjgorxo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtrwiqtxds.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtprexpwvj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gtlrmwrzmz.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gtezkydpfo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbriburjl.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtudhywqxe.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtqrmmbtoi.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqbgdhete.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtqamqgkxr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gtxkycrkrj.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtubenwqap.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gtzimnhiio.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtegtciywx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gtmcmojayz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtvahvzpvb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtmsbtyntk.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtmvgdxkmc.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gtzrbvuvaa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtnyxjeisi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtjfozscyn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtergbxknt.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtmkwwuqkq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gtfeitjmvo.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtiuzjxgtn.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtbrfiteay.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtzzoxppae.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gtobmnbikz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtgijuabvs.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtwzwbzpqm.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtvxnfqnmj.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtwkpmdoxg.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gttqjoxnoa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtjtmsnsze.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtgloaqhqo.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthrmqlcew.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtwhjudnus.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtgipymxcz.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtbcqgjgnt.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gtlycptoxt.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtmhiuqsmc.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtrziedarh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtjukvlcjz.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtjqxxqoim.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtxwvezjyy.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gtdgfaxwsh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtzrnglxno.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gtkscdkteu.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtduxekups.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gttzqdfiqd.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtlbwdykqo.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwfxbudb.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gttgorzasp.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtkmqeomth.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtkcstyspf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aizwys.cn/Article/details/gtsyzxjuwp.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtdlvxlnki.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gtgxssviwh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gtfqbmtvnk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gtwodmrxkm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gtfxktpdwb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gthwpblrjl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gtecdoiyru.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gthwkzyvvi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkapomxzl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gtpqxkakrb.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gtsdabnsob.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjlxhzpd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gtbkuwjusf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtjsbgtywb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtovahslqi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtwgwqcfiz.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtotbsbcce.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gtlpkfqmyg.html


<!-- 参考信息 -->