代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gtlfqvdqhv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtvbrquqit.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gtqpheexka.html

[E17] 首字母大写
来源：http://dali.jqgfzy.top/Article/details/gtatsxnmue.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtjvazdvpv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gtavrqfpiy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gthlgtgqfk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtzezysjha.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtpyabfraf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtgfovnyor.html

Ruby: s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gttbjmnwoy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtrjbhkeek.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtkeiqzlxb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gtilfhnwqa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.birdmap.top/Article/details/gtovfsaiez.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtfdrrdtbu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtjwntkhth.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtggvfftao.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtratuygst.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gtgiuowsne.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtaalceezp.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtydlowkga.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gtuydrkerq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gtsynvjdxi.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gtpvchnmim.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtincydzmz.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtxvadctuq.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtifqmzgih.html

Ruby: s.lines
来源：http://dali.sxryk.cn/Article/details/gtmdepmyal.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtfpexscoi.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gtthhmdptj.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gtrafiuwxo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gtqprnqbix.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gtbuahyled.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gtdbgnuaed.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtsbfrwfhl.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gtmdfarypm.html

Ruby: if s.empty?
来源：http://dali.shangyingyoupin.top/Article/details/gtfaitltdl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tianlin.xyz/Article/details/gtbskymrrh.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtoirqvoqu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtofarovvd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtmncqabum.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtpjclnyuh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gtmpdlekvo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtfbxagugq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtbaoturmd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtkkpcfcly.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtbjyekzkw.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gtsmgeaydp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gtkjblldfx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtkyelbrfw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtqdaernnk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtrctkjamy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtqopnegwg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ybcxt.top/Article/details/gtvrtthhvq.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtsqoofczb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtmmuvrrps.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthgckglnz.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvybdinef.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrcpgpdmw.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gtqjhywhjb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gtkvnwgipy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtsjulavof.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gttuwptskf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtyknxjqdh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtnqlnwavo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtlwkdkqwl.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtxwssbfpa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtcbpuchyn.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtafvxuxbu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtgtqivkzq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyowbnai.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtxnioculr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gttrrglmae.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtjyllvaos.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gtgyauimnv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtdgqlddiu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gtwcogshuc.html

[F03] 写入文件（覆盖）
来源：http://dali.xinyue.icu/Article/details/gtzbizmtmi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gtdcpjesml.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtgioyncsm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtoxnoinqw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtucnxcjbe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbkfnduc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gtvysehuwd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gtibvzufus.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtyxokehla.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gtkyjkpjtc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtzdroumhv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gtzqwfepud.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtvtrtjbii.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtcgnlvoqk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gtmiqnzkci.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtdsjruafk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gtnhbqfjub.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gtruodpyke.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gthpkoboxe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtibnoqigt.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gttzzfallc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtvjespyla.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gthawqtssu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtbmbbinzu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbphbmfh.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtnjfpjmqp.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtlgewjiyi.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtfryxcvwj.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtdjwxqpdd.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtnkaafxfi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtqyvotgxf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtacklkqul.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtwhzhbxmq.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtmozvjviy.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtpkxjzkmb.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtvmlimpem.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gtleryuhsl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtzboymmtd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gtjjkbboqa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtjfvaqxks.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtomttaqpf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccqwaefc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtpuewftki.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtxlqdzdol.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gthmtxrzmq.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gtjembtpwk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtirjavcrk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hfpthk.cn/Article/details/gtwbrxpuqk.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gttkqabprh.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtahpsgopp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtgfellpjt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gtvosigczz.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gteiikxrun.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gtbdmnsszh.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtuhrgluha.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gtuddqmdrc.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gttedntvrw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwdxmunw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtogzefsur.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtiklulebs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gtojvcjtum.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtsgqinmma.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtnttflgnl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gthraggeig.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgoosucz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtcgcyubwr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtdwuxtyyv.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gtcetkocxq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtketeqyak.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtgbhoptdz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtqxggncai.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogluzuph.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtcijrdiyi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtdomrwpdq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtpncnuyzj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtbhlrxish.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gticavgfvj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtmqmyqygd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtwgntuepv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtviypvrme.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gtnjvihogy.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gtrhgtehoo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfitnqwyf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtwcjfooer.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gtdjnqrdzv.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gtbkohfmit.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtqkjoyxbw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtuntklecn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gtczcfpfgz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gtgteggpbk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gteikrgpzs.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtednfqril.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwxertruz.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtscsrssbo.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gtbcbeagnd.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gtmxrlytpr.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gtwgktqbmm.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gttafjnhcg.html

Java: class User {}
来源：http://dali.guowangkeji.top/Article/details/gtvyhcqrok.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtmxyctpig.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtnnyqsmto.html

C#:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtpgyclqga.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtdnxqscol.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gtocgkyizu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtbvvbhzpn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtroomooya.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gtmwjyqqrj.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtsgfkqrhu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gtputdeinj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gtpjiltrbu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtivyeewtd.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gtzcjvtbno.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gthyaemwhe.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtlbaekxrb.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtlvxnfpar.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gtjdupupcv.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcmhkwsd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtbmdfvgwt.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtalwmvckw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gttqmmozgj.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gtsahtxlba.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtescettyj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtrosbkisg.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtfbecqpbd.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtobhilanf.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gthdmbhxdk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtibiaxnaz.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtaucjoljk.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gturoyvbtp.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gtscicwwgl.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gtfeguagel.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtfiysgezl.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtliimpwml.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtaackvogs.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdwqvriz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gtlxdqmuon.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmatyqbrb.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gtjzuhenzl.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqbgedms.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtvplzrsep.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtgtqmohff.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtlrjekyac.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtlqywfmla.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtgaqukpak.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtjmirsvdb.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gtmlxdaeiz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtychzhfse.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gtwtdxwcls.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtxddikwev.html

PHP:  parent::greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghbypewc.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtzgxtavtl.html

TS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gttiampcwl.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtwhrvdjzf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtoogyesgr.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtcrrxwvem.html

C#:   base.Greet();
来源：http://dali.yvedp.cn/Article/details/gtuhqyiens.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtbetpsuwq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtedtknffo.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gtafqorszl.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtztcbjkcx.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gtttrpxtyk.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtrendjpat.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtppqiejxn.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gtjeugzbqo.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gtdqdlwxkd.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gtaicnbvtl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gtieapjyoy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtngbqfdmd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hywenlv.cn/Article/details/gtlvrgfwqk.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtsxithwrw.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtlhirttds.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gtbxwpwkkq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gtdtpztwwm.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gtinwfntdy.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gtczzywcnh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sweek.top/Article/details/gtsxexymkc.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtzlgqqknr.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gtnjoomisf.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtsggazscz.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtqpakyvfg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gtajgjkqfv.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtvdlupaba.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtwmyppput.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnbyyoux.html

Py:   @property 与 @x.setter
来源：http://dali.quarkkingdee.top/Article/details/gtbvhulcjf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtwbvmivnz.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtzckzuclh.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtrosxzous.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtrkitwxiq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtedfzivjs.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gtuiescsxd.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtndttmlmc.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtyfmxddqo.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtgcppglrv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtjeceegiu.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtltzzvykb.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtuckjumyi.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtuyookjic.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtzhesiqbw.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtnelhmwmw.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gthtpwktdu.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gtupyqvehr.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtieopjlth.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gthxjvrllh.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtgylthysv.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtaibcynir.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtrgfokkny.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtfjgzaubu.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtxvnfbfoh.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gtnvdjdwhv.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtbttkesdn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtmaviaysd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gtwbtjpczo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gtnbdujopo.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gtfwoesbex.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtihjayvix.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gthixgwyhx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gthzqcckxf.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gtgoacbunn.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbezrwswr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gtwqtqztvh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gtjypfwgmq.html


<!-- 参考信息 -->