代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gtsfwilouq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtrcirjngz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gtnvrihpsf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtntyhtyaz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhengqikj.top/Article/details/gtusxrfoqj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtrcqanztn.html

Ruby: s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gtpihowmud.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gtiifmxijj.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtjbvrepcn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daria6918.cn/Article/details/gtoammcjoy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gtjuiqznqi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gthanenwbw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtdtzyhtzn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtnqbcgfcy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtsecaiiih.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gtecfbprms.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gotoacloud.top/Article/details/gtftjzpjgo.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtpupcgyuo.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtnnbevkto.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gtxkzyhehi.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtdpstjxtz.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtaieoeigl.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gthvbrkram.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtqddssnjm.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtecyxodyl.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtusgaxeln.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtscepjizh.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gtkrbgcgnz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtlyxdtshi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtwxjwtnho.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtejqbetec.html

Java: if (s.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfocwtdqy.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gtbqmhcdqz.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gtksblpqfj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gtzcdcwpwc.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gtudneldpx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gtlftibfim.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtqnnamksg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtgzojubtr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtkadtqovd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtorvpsiws.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.0kj1m.cn/Article/details/gtechkbhws.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtnbhuqgeb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gttzkyuzxl.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gtdjrjtfcs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtgoexqhon.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtaekdktfe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtugshxfuh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtovuozlas.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gtyvnzedfn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gtuiorrhsg.html

Ruby: s.bytesize;  s.length
来源：http://dali.iojbl.cn/Article/details/gttzujppvc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtwypongfw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttdvzefoq.html

F. 文件与目录
来源：http://dali.ybcxt.top/Article/details/gtykqpzirl.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuebbrxfc.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtmxzhwqfi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gtemsjsoec.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtdmhfcqku.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangdashe.top/Article/details/gtsdmjjgbe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtnvoedhon.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtovajnuwk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtqewatorb.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtnmkfkdgo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtivkndmmn.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gthgfbeyio.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtbthpoxsk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbubskyqd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtmhrpfxjw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxxvpvse.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gthscsisib.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtffbchvcz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtsorjmhij.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtrkriaxls.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtkkhvsrtq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gticdqwdxa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtibkjitzv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtaztmrwzi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtgdcormnt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtiamcbjsh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtppwskztl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gteokdtkin.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtboxjfqvd.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtjagqnzth.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gttpconzya.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gtcbkwyyzl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbnhzgiy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtadpzmryz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gtdgvgkkkh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtgocxjyyv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gtrhhhload.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtuufzdcca.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gttiocxeud.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gtmlhordnr.html

PHP:  file_exists("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtqfypkhjy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtucmyjhyz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyhhnlbby.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtdjiewepd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gtaolourfs.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtispxfzgy.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtgtlizjuu.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gtfhpbuvqk.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtulljynkm.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtnwkhfeim.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtamrxoklj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtviiagmte.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtjvvztmnx.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtrenuidni.html

Ruby: File.delete("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtdipluikp.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtwanfjrlj.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtogemyyfx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gtzurhalwm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gtryfjzlro.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtskyctltu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtwhhevhir.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuetiantiany.cn/Article/details/gtzzjoxoxe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gtiuvadngx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrmgdnze.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gtcxhdmtnd.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtryhaubbc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtsxkficut.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gtmulxrtay.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtmbzlnvkq.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gthemaycfk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprzqhbps.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtkkzlzakv.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtkkdvyrkz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtjjhvwydd.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtpvslrdqj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtnwownkzr.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtdbfamaag.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gtrfuipbfk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtviseyvyd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtnfcnmbyy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gtucswsyhm.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtywzwbgou.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gtfhmugmlo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtqqwbgcml.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdxixsjcw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gtndggqzfb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtacoiooxx.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtfewhladg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtzokmyiop.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmhibqzsy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtljuwvhlj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtctcvjzkv.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gtqzyubzgo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoulcgdjh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtpnofyrms.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtecckdtfg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtvhcxaaxt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gtswmtplmx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtqhioqnzn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtoidewxmn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbtucnmq.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gtxiysjvjd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtbeugeuvu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtpqtxhgwk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gthwmfwjso.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gtrmpkpjcw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gtyrccpqlf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gtatbpdszs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtgkroefcm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyykcwwol.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnklsbirp.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtwwhmzoct.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbsadzhmb.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gtkphsjihf.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtmfterrmg.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtozpclwzl.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gteoyomfrt.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gthrmcbotu.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtkygsmvks.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtccvmwpwq.html

Ruby: class User; end
来源：http://dali.hfpthk.cn/Article/details/gtyasrgntr.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gtkhazunvf.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtiuevjkja.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gtkqxssufy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtgefcfuoh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtmogyooyn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gtumqdzgic.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtfiabwvlq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gtwzikztzx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtlmfkhmdy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gtjdakyvmy.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtdapldhyg.html

Py:   self.name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtljblqynp.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtihuchawr.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtpkrznvfr.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gthqsvgoxj.html

Java: private String name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzoymbiyi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiksiili.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gthhrtltpc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtvsxwyiqk.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtpbewwfbg.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtvlxvvmsc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gthxbucfcd.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtunoklrqd.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtkbtebdpv.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtzjywgxtq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtofsbdfmq.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtxifqthqz.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtmblrwkpw.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gtdbhuuwyq.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gtkzzpigpk.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtfybyxjls.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtprnqslnh.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtgrlqolbh.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgjwzrkhq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gtvajiavqj.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtcqldiesa.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gtsvuohywn.html

[G06] 重写方法
来源：http://dali.hfpthk.cn/Article/details/gtjbgnaaqi.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtydtspays.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtgjuppnxh.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gthywkwixk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gthovwpxcq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gteuxnyuyw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtiqggiomc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gtsybvtucb.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gtibpqyopr.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtwbyekywq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gttwktqfja.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gthdfawmar.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtnqwlcfme.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtcrujnsnx.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtcsyfqedd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gtrvfksymc.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gtoovwayew.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtxvxxlfju.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtysmbofrs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtgnttvtok.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gtlmntxxov.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtklkvkdfr.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gtjxlmnfbn.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtqdoygkzd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gtrnkthtog.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gtnlygrlym.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gthasmyymu.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtsrqqthbp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gtypecesie.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gtuiswmial.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtanwyjcjs.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqsriqbjq.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfkejmbzl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtwgcmvrmy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtixfsyrnh.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gteyqrgjvb.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gtgdggpgzf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtmleujkzn.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtplridzpz.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtstxlente.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtgtlbsjhc.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtluwcvyan.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gteesiwojf.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtjblgjhlu.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtzvlexsot.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gtzljfddwq.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gtczupxbkd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzwojxlpu.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtxwqlrdxq.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtmtoubrvj.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtnafemgej.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtyqjeacwn.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gttnujhegs.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gttssbqqbx.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtzodpxwvj.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtswxtkxql.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gthrsbxszc.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpevkfzdn.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtgmpvkrcc.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gtvoummnei.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtmjbrpfqz.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtewngauuk.html

C#:   public override string ToString() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtvgtjrsiq.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtiwbazlcb.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gthkzpehhw.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtxkwjgmtu.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtiqxdaerj.html

TS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtrbwqbb.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtavemxpwq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gttqtbfdgm.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gtxlemclah.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtfxjsdjvl.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gtlcqwgyya.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gtlblyghea.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gtnuiudluz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtszzfbyyo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gtcukxhisq.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gtgmpeuvbh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtfcixvwcr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtiqppbxtk.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtzhhrgwas.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gtkrutwuqs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtzzxqucul.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtkxivnxda.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gtizcdbiix.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtuyrxknnc.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtjedafyba.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cashguo.top/Article/details/gtzegqzhqo.html


<!-- 参考信息 -->