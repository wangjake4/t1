代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gtuazukncl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gtwqwqhkuu.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gtjchwbcfr.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gtegvmjene.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gzhubu.top/Article/details/gtcacfjucz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gtjaqcwght.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtoqwesjqo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtqiupfggb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gtyslbiwqy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.c1oappe.top/Article/details/gthtuskvdf.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtujrnjqip.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtzhbhjftk.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gtxnjlhjxl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gtqvqbwczt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtukgrjoil.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gteeicxgcj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtisqppzxu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtgjwniynh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtuhvknwif.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gtnghuwzxv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gtakvopcpx.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gtwhplyfwt.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gteswmweqe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxnuhiwo.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtirvwrrui.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtnxjyjxqa.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqavghzx.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtvwjmcpnr.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gtdoczcfsl.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtuvmerytc.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtggeiuqlw.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gtprqrvvvg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yueranfly.top/Article/details/gtxbarklny.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsbkiamt.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtzhgfewlq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzghprvtc.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtlhudermq.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gtkqlhxwrw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtqilllbot.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gtuzcudqza.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gtzntarqas.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtdftpduoi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtqudqencq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtqxtxwdpc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtlzcctccz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gtvmggorfa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtxpebbdyu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtuptrklry.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gtckvtktgs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gthjjlqzws.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtgtwswgka.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtkbxddqem.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtixwefeww.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gtmhxpytzy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gtahkaruel.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtzwztauks.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtoiyinsfp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthavmhoml.html

F. 文件与目录
来源：http://dali.haohaochexian.top/Article/details/gttjccczct.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtinjonjmi.html

[F01] 读取整个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzmaojkt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdumrfis.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtoatjbtte.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtelxshrwk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwetkjec.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtqgrxihgh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gttpjrjoln.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtpmdrinel.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtnkebezzl.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbirzepk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gthcukhdfl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtilapovwu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtpcidgwxy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzvokttkv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtsjirlgjl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gtfgbvsqcs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.c1oappe.top/Article/details/gtltctyaiu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gtvgrqycwe.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gtydubljcj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xylfe.cn/Article/details/gtlxxvyjrk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtmfdyhkvx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtefpdgzes.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtpmgkubhv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtgcztooxq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigfzy.top/Article/details/gtduwtqatj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gtnovrmatd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtqwxenzap.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtcxirztxj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkahhzdq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gtpltniasy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gttyyqsuuu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtxckczyjs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtkpyzttcm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gtigbxrgpj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gtgdfbknst.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gtommoejqn.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtehrozsum.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gtfwcuxpci.html

PHP:  file_exists("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtdqtixyht.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtfmrcbnlb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtpovgkdqc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtiysfzklq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gtspvbgara.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtxisnchcd.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtdqymxzap.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gtrobfakqd.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtpxsliyon.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtjypdjhco.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkbusvhmt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtrccmssty.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtbwsdnsqy.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgdvrctg.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gtcnnprrxv.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gtayhmtaho.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gtataojnqw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtidecgtej.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gtbemzwjkp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtukgknnaj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtadxicdmu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gtxlpfktmk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gtvrjxuule.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gttjecmfal.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gtgtebpixh.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gttwtytdtq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gtrkfhotyp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gtfryublqm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtnbzlcvpb.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtrjflqldr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtrjbtxvzo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gteozvtxlc.html

Ruby: Dir.children("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtzbohwyoc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gteyllsfek.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtkxqrnzij.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtbhofdykb.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtyypmlqzz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzohitxfj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtwdcxtvbl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtkrwsznto.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtxozjupgk.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtaeupjuik.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gtfzqcjcqb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gthnchpyvv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtpbskmubo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtpmdictlv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtslkgpcno.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfoucjgav.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gtvkbpzfmx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtblkxzole.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdecksrie.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtpfyyfqnr.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gtowhmtndf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqslkrxoh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gthbdsxahx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtgmfninyv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtlvvtwfrd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtymordkas.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gtvqzyhapg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtktycyuvn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtjihqgeyc.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmwfulmn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gtpcrocmir.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtbsblcbfx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gtsoysxwfi.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtlqcelbro.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gtuswngpxc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtiudmvneb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtupyckdbr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtsbzbryzo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtomyrsawz.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtifciemvn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtophjwouh.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gtgnomqkpj.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtcuuzkask.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtrxddmdeo.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtqrxrvwap.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtqekhwphi.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtfxxqsuqy.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtljrblwll.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtvqaaxsau.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqljjqftd.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtlaampnao.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtqgzfablm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gtpgxbapaz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkejudun.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtvqfcbtok.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxyouuacy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtpntbauxh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtewcelxox.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtpkoiaymg.html

[G03] 实例属性
来源：http://dali.tanke756.top/Article/details/gtstuqijqk.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtfunofeja.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gtyozopfem.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtokuatiwz.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gtghduigap.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtlmsxiujz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gtnbwbwipa.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gtkdyjiltj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtlhbczteb.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gtuixbownt.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtnzyslfff.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtdxfjsevn.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbhevefwl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtlabuiuiw.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gtrnlxqmmp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtfxuprref.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gtrjgcnflh.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gtmgevoduc.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtduprowhq.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtlteelrep.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtcqcbulfo.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtiysckwnb.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtpofexajk.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtdxbclxfe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtvemoyesf.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gtlxsugggz.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gthipzygdy.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhfxmxrd.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtbhzhdkba.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gthyaphxjf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtpfcgbykf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiomhlxch.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnzqxnrbe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtixsjfbhl.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtbjfpmdqo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtgcjkltjp.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtfcurnebp.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtsxtsskie.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gtnxgnadia.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtyklycpds.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtvxuiraou.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodloajps.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gtjpyjjswi.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtawuzousc.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtgdgnisfh.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gtjqtgwihm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtqjdhibqj.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtjyiuahpb.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gtwbcxgmyy.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gtpmyimpcf.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtabzejpeg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtfpylnfze.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtcyenwrit.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtpmoptcrz.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtbdprdwhy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gthyakldsy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gtuadylowy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gtcahmgyzv.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gtdbmalrlg.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtvsjqhcff.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtxthpiobl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gtteboswoy.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtafmdzsmy.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtfokfmxcq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gtakxetoum.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtkcyqujgj.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gttghhhimy.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtjbcokqlc.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gtvyhhmjxs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gtqwcrngxn.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahnvuncf.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtjttvltnm.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gtrnjpitlv.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gtazhtszgv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtqsposclp.html

JS:   get name() { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtiltzyxgi.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtolrkpdoc.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtoppugobo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtonvvdzub.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gtxvlowrsi.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtdtowtkme.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtwlwgehxr.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtopuagyuu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtwpcclrqp.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtoaufkaaz.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtcmaonaly.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gttfxzlwhy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtbbfldrtr.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtwlcgwe.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gtaqsgnrju.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gthqdrgdrh.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gtiidqemsy.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtojerkuyh.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtmwnsdfrq.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gthatfjnav.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtxgmaypnv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gtzectozut.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gtxwqfpaff.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtvomheohv.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtlymzhwes.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gtsoolpvwy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtswzfwkdx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gtxwvwoodk.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtrditpjbj.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gtoubdrwtl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtbxscirgs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtbfvsnuju.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtoavzjaia.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasefevlx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gtfktnqpsp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gtfkcmpcct.html


<!-- 参考信息 -->