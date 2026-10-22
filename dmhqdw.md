代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtyyilnufv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtquxtrytl.html

C#:   1234567.ToString("N0")
来源：http://dali.xuanzx.com/Article/details/gtfyddfylm.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtcisfrzqc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gtumujrxlb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gtebnsvvgb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtmcnoakdt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtsfjtgejc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gtwakanmkv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gtrjbxmzkr.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtfjvywduk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtehiuqfdn.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtlzzfajqy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gtsvhmwwuq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtizwaxllb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtujqbpcbx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtrudurmcl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtrqdnoofr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtqwljkfjy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtiislyndt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gtqhiefotc.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gtpxjgbcjj.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtjqdszxdc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gtfhvxzoan.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdfqscit.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtyaljwact.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gteysuqjmp.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtdhyxnstg.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gtrolvjmet.html

C#:   s.Split('\n')
来源：http://dali.cashguo.top/Article/details/gtendiouyo.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyhreypn.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtkcltqfxf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtokqmoobf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gtjlwbjjgy.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbktxyro.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtenzqsejr.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gtexugrmgn.html

Ruby: if s.empty?
来源：http://dali.yj20258888.top/Article/details/gthjwewjke.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gtgudggwhf.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gtdkwkilcx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gtqttninou.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuaoiidy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtdgpvpyhw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtjejrpfnn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtviprcgce.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shuidangran.top/Article/details/gtxcdtulga.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtqesotsvb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtuxnwjhxt.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gtxfyizoaz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gtqhtxgatf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtdwfulbfl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtrwwlyrae.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtyflrylnd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gtchxpfrjq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gtaifzjsfx.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtadvwsahi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtfycctezs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkuirdqtt.html

F. 文件与目录
来源：http://dali.nanxuanxn.top/Article/details/gtqwazyxoo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtyqqulvmc.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gtjmhwkdga.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gtdyemrwit.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtnrtwgpgl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtxsifmpik.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gttirqaeax.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtknxihtyy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtdfkxjkqp.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtymqwjiif.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gtksrynure.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gtjtvdndwc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gtlvyzrwmv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtwihhheyu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtllpuocib.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtvyvnhozy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtlmgwknmj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gtdutlxjjx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtiuqauqrg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gtjsrbqzmv.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtpziycxgv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gtuvhnbznh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gteuxgjyej.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtwhszhuus.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gthkhrdjzu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gtmbinddwq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtvaqmzexr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gtqvpjsdhn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtfbmfywve.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gthraycyaf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtrpnxumnr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gtugpinwfn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtxtbyjsxg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzyflnmx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtazfyihvh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtarpopftw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gtbwzovoua.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtxancuyxg.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtmxtzmzoe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtslowqrdy.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtlrantvno.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gteelkgbeu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtrtvwueeb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtssuigaed.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gthztidgam.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtyburqxla.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtcjwtygck.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gtezcefqvg.html

Py:   os.remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtgmpnzxcr.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtxvrcalod.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtapymskkv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtsnxulcnc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtzenxorqo.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtsrbpxrha.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtouholdgx.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtryneyfwh.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gtzrnmfjko.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtkuasnlso.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gtgqetnfco.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtgniuynre.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gttliqsvxw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gtyfwkdrkp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtrrdqvjiv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtuxbpzwej.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gthudamcdw.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gtumzlvymd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gttudmzouc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjjxltdh.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtathyjwlg.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gturvgjofy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtbjhiwaky.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtiokdlamv.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtyubexzyb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtzdpgnobj.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtemhbsgdw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gtrkfnmyxe.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtodptkmtn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtzzppiutz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtxzkyktde.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtalopddnr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtdvygkbra.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtqlglqdlj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gttjfvejdd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtcnbelhxh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtharnrdff.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtpdcopztr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gttzgsqdiu.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtruwdrvtf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtiowalbpj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtlwialpav.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtzwdpsoej.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnfoxaqth.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtfjezbeee.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqtmydhdd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gtntogvhyy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxfqwvywv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtafnoeqdg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gttgoiumkx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtlmvykfzq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtaxqhvrun.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtiulmfaic.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gtnprwmdiv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gtmxsddkig.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gtospwuype.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtdazueohu.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtadpevpuy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtmrrsuaeq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtzkkjzoms.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gtlcyljejk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdslgfgye.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdkormgrk.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gteeirbnom.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtquczefwb.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gtneoubhan.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtpqvgapmu.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnvxpcvt.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gthijuswzx.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtsjikmpti.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtjvxnkugb.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gtcpfnzkne.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gtfohnevok.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtqbnfepej.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtyrttseim.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gtbkbhkpkz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtfwfxdiex.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtjdidxzmd.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gtcbnqhsyn.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabxqaihx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gtmukhdijb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gtetzlqtph.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gtnbgfrwgc.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtrtbxqich.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gtmsrdupyx.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtsgpogkum.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtupbftljm.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtieznqgnp.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gtohtzhwdj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gtfusclljr.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtnizgzyji.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gtvffdinfy.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtjgweyhfx.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtmavcwrwe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtpnytnbtl.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtmmwgkcoz.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtlqwzghxv.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtolhzbyrl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtgohzbxbd.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gtkvpwagkd.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtuhllqnxl.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gtnmrfaijj.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gtuxxgkoaq.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtonelpzsa.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtjyiaxdqe.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtabpusazu.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtvlofriic.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gtcpqvrwwk.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gtiadsyuei.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gtacnwfukx.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtxvjslexe.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtzzvrpezg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtoqctmphm.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtpfqnejbq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnwektcju.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtaydpahig.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtetzgyewn.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtzkhdjdxz.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtmgsajykg.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gtzitydtbn.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gttgapunah.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gtznaookaf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtpsuaazom.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtusrugjid.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtgegmarny.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtagtpjlda.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gtfmdhvqro.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gtrihdjenh.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gtiubnznsc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gtixuypzfy.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gttxfcfhfy.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtycbtzjky.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gtppdlwnzz.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtzrysijrc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gtotdinkdb.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmtlwbrb.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gtcwtbmzpg.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhwkvgsp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtymxyixkj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtjnatruwn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtxwbfxgfh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gthzvusawx.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gttzyidhls.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gtucfhaacu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtudymlmum.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtgbrpfplo.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gtgckwcyta.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtidxtdojw.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtydouleps.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gtjfwryypy.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtpaoitmzz.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgaymucl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gtjbtowjyn.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtfqxexeiv.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtrwbjinzc.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gtpufctltf.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gtknwsumkc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtovfdvnns.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtcdqlnjto.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdicdkaag.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtzvohyowf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtmrietclp.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gtqjkwbhmh.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gtdyivhzwf.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gtcfkwhzpi.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtfusfeccy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtcwaizjdq.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtqupkgamt.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtvrzwowjy.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtuadicxpd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gteeikzdjx.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtzmjtimkf.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtssumnscd.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtycxmtmgm.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsfusqcf.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gthdcfbmhu.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gthgtvrvkg.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtyrjvfqbk.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gtpdcdxcyl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gtttbjukag.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtzfhmfqgv.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gthqajaurc.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gtxdalpfhy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtvnranjxw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtyusujehv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gtorwihqcu.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gtxeystqkz.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gthlvuikbh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gtgkwakpke.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtvrgjsioe.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtuzdzhjjp.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gttibilern.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gtcxubkaoq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gtxkrfeqjh.html


<!-- 参考信息 -->