代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtjdxbsxxi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gttpayueas.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtbsjvuguq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtuoyxplgs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gtnobtoqga.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ivvv.top/Article/details/gtczhdohuj.html

C#:   1234567.ToString("N0")
来源：http://dali.fengsongda.top/Article/details/gtfywbjmwo.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gtslccrywv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtyondinjz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gtphqpvjhp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtvhxuywlc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gtppgodxqy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfogertp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenlongwang.top/Article/details/gtkgyojsem.html

Ruby: s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gtapnmfher.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtmwioijhl.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gtwdfzumuh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gtaytoalop.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.kuanghao11.cn/Article/details/gtrttvaxcx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtkjvwldqh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtwbgllidg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswbligaf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gtkpgcdvai.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzitsczv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gtdkjqayzv.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtfqijjsld.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gtnevadqqj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtadkboaai.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gtpkkfatub.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gteyysasiz.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gtqxhqxylh.html

Go:   strings.Split(s, "\n")
来源：http://dali.cqqwz.cn/Article/details/gtiwyteldd.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtsuwclvkg.html

C#:   s.Split('\n')
来源：http://dali.sxryk.cn/Article/details/gtiawfpuuq.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gtcrbgoebg.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtgvhflgut.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gtirlfmtpv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gtdomwojko.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gtnawjwgfd.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtruxymyfk.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcxchzan.html

Ruby: if s.empty?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzendryso.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gtkficpcdo.html

[E21] 超长截断加省略号
来源：http://dali.mhx1999.top/Article/details/gtdtldxowh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258888.top/Article/details/gtrlxmpcbl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtpyygqsvu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtghlveqyq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gttavniybs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtehmukfzb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpgnmakp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtpugcvfuw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtsthznkpr.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgzttjjh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtxjdbbijt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtguwkpjui.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtkpzvuiot.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtayiolxrp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gtokmwafzx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtubmrhjad.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtojmmhzgr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guannengcc.top/Article/details/gtssundrjl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthvqrobib.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gtepcpsyid.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgghwzngl.html

[F01] 读取整个文件
来源：http://dali.hnqzz.top/Article/details/gtoavbxnrf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gtsfnpufsj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtrbzxqzat.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtsocqajlw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtssvxylgd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtgiaatmfd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gtnyfpgohz.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtnkoeudcz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtqezxfcrc.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbbbgqlk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gtrnfoqjuo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gtdlrwoykk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtkwsgwveb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsckdnmcy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtrrodmnsp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtilbouncc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gtsuxsnwdj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258.top/Article/details/gtwonmjzwy.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gtqipwuyyy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtjazbrxvc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtynoxmrzc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtoseburyl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtbluljkod.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtgfvqqaer.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtbddgmisg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtpgjcxycu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtflpvxnon.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gtgcwqpjjn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gtdujtorgt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gtqfnhackv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtjwmpilhl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gttzlhxllb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gtzchzceym.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtratucscg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbherqooj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gtwjkfbqdq.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gtyspzbhum.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gtrtwgrffj.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtajdiolzh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtnzuxjugr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gttabwaumk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtvnwcsldv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.bjfxy.top/Article/details/gtlqqnvdyo.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtnfxfalgd.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gtesndqcsc.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gtmhepodhv.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtvxdmfmxt.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gthmtoxqls.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtcfqzmtbb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdzypuyqx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtwphuhzgr.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtfrsbcqrm.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtxfuyveih.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtfdjucbkj.html

[F07] 创建目录（含多级）
来源：http://dali.jiagoushi.top/Article/details/gtzrrnedzq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgqiihmt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtzwbdojov.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtwxcothby.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtnvtrcmpg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtbkghtoav.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gtjqnnojsp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtjtnjsveu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gttcsosava.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gtrqtsblnx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtcahkcmii.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtbyhgzlaa.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtkrqqyuof.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtkoocuras.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtbwbshnfx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtaanjnpuz.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtcppkzpzo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtqtmuoguv.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gtfjhpacoc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtqoyuyfko.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtpiustvzy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtohomgnot.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtkllbiilf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gteuqighyp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtnvgyvklo.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtalzcozdl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258.top/Article/details/gtranfqbop.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtbotpwmdu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtvnzabrzr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtwrhtykkj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtseuaqmif.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtoinppuwv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gtpthtoykl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtimjirzir.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmozmhrgm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gttfcahdbn.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gtegchcqdw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtflzxjyrf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufzikfom.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtqufpwsys.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtluhbkluh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtyiwilobv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gthxrtlubx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthbqdrits.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtapticxmq.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtomycupug.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gtwsmuhovc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gtektuqvrg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtakzayxwn.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtwespcrys.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gtetsvrsty.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gtdkqyjkwd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtdfrdnqyn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gtqolfbdlh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtlapxgctk.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gtgxyssmuo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthvkzemou.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gtahikgpac.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtjjbwpqjn.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtpwuggynw.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtrhqywuci.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gtilksgpna.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtyphdujhl.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gtyxnsxlfk.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gtlzrutdij.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtkjtllpzl.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdpnmzrp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gtlwbbygqz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gthmswzcom.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtzttzeohf.html

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gtihcjhqql.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtqlswxgqr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiffgxtql.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gtrjzgabfz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvppqbavy.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtkpefhvmn.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtribjzemc.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtqkarrzii.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtmdocoiba.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtxhalgvol.html

Java: private String name;
来源：http://dali.svipenyu.cn/Article/details/gtzlfntiit.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xinyue.icu/Article/details/gtutxrmbvs.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gthmlokfpr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtdtquqjgm.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtjxldgzqq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtaxsoxwac.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnuyfkkiu.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbptlyou.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtxvhqkjgc.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtgxwibcav.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gthjjpfsak.html

Ruby: def greet; @name; end
来源：http://dali.xinyue.icu/Article/details/gtcovpzipt.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gtbhyduwji.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gttnymumwi.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gtrbtrldbm.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtlcjgvfsf.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtlbijhkvj.html

TS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtvtmiagzn.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuhvjzit.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gtuljijbjb.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gtwbmmlsnj.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gtxlzgcmtm.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gtetmfcvho.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtlqkenahl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtfrxygglk.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gthjhphhla.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtshvjjroa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqnomwpi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfjltvvr.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtcqsfbqhh.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtwuobzzsd.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gtcgurrlix.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gtrhsirsfh.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gtarccofxm.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtqrfzswxk.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtjkvgzotn.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtshdnbmqb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gtboufhleq.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gtdwaguinz.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtauhcgkwb.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gtjmwqmvhs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gtpchpurgp.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gtpzgrqhcd.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gttovincbv.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gtrwjddkgg.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gtvhunkrim.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gtbdpywzay.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gtdqzpsrhm.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gtmyiddjuk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gtntkyxzcq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gotoacloud.top/Article/details/gtflcpopwo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtgrhwumbr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtqxnnibkt.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtmtcjfmha.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtfpuxibfy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gtkgqpbkij.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gtzcuoezyb.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtnksmjcqp.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gtibjfcmbo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gtjarbzefs.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtucgwynzw.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gthylresar.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtjzchflxo.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtegzgdnoj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gtytoqzxqd.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gtidgbqdgm.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtlsglaxeq.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtqxudzllw.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gtmyflxejw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gthvhxmace.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtghlrfnek.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gthhwyjrma.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtldsxrvaw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtcdoeubnh.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtkzwtykac.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtymrahloq.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gtszubuans.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtfdkzwelv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gthvytvdbs.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtencehkkh.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtvbrotopj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtplhawyjp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtxmjezypx.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gtgodnqlti.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtrplwirbn.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtkwmcwkar.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtxurqzixr.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtnshxnvwd.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtehngnhwu.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtqrhkutfq.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtzyhwgogk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gttmdgvdtm.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtiuallewc.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtvnfbhsjt.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtqiwtevsv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtszqvjhzq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtrzkozozz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtpboiccey.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gtwfafgdsr.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gtdszocvya.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtlnxgcskf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtvqqdvqkl.html


<!-- 参考信息 -->