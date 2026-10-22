代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gt2lbanhmru.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvirjrep.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gt2hzaelzku.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2vinfaofp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2emhubnla.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gt2dinufpuv.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gt2znbwezue.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjvsbmoh.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gt2cmbzhlio.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gt2vvppjlrm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbmqgubi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2hejfylmj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2hpsnjfmm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2gxwwyebl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2hynmumlt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gt2hsibchgj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gt2lipjojad.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gt2rpdjfgit.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gt2rygfhiul.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2zvpimozc.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2szmoaidx.html

TS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gt2wpgzprvv.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gt2nivzgcpt.html

Go:   strings.Split(s, "\n")
来源：http://dali.c1oappe.top/Article/details/gt2ptxolgnl.html

Ruby: s.lines
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwzpehgl.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gt2ogxjafth.html

[E20] 判断字符串是否为空
来源：http://dali.dashuyun.cn/Article/details/gt2siewrvzf.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gt2vtoaauji.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gt2cliwakug.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gt2rlhipuil.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gt2gbvlgfcw.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gt2lgyszzxy.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gt2qqtiklrz.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gt2rhfevuxi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2vzhbwxhy.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2wiaizype.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gt2hywfoift.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvwupomf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2vngzwhlk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2rvzltfuc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2brcimssr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.9152youxi.cn/Article/details/gt2txmiwvxe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcpcumcq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2irchaoha.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gt2qdeawmvt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gt2jhtuoxmu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2plurthnv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2mtvdpjht.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2einraeto.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gt2yygelnbk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrtpoikj.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2crqpetqt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gt2bioqaenu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ssafemyx.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gt2xsxtkgsz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2bicxqzdw.html

[F01] 读取整个文件
来源：http://dali.0kj1m.cn/Article/details/gt2wzwojeqs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gt2icizqqcz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2fkdmggtj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gt2peqzakco.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2ncomdtcv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2ixrwieui.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gt2hiuuvgxd.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2zxdyafec.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2zrkpqugz.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gt2oarojqaz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gt2niomieah.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gt2aigxftcy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnpgeqag.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2qslkavvm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gt2thdmjkdn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gt2kfajqoqi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gt2eqqjlnsd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gt2vpxnkzuz.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlzkbhpb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gt2rficlzzs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksjxiovw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2imnpysqk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2lgzxrful.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gt2ikkcujqz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihtaowlo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kuabysgo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2bieaajdc.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wixjxids.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2kvdrxtww.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gt2htytjmci.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2lrqnzhhe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2lvamnkqo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gt2gzbtylnx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyjhimin.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ydzc1.top/Article/details/gt2qmzvdwfi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gt2fjlkzaha.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gt2bvboxrrg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gt2ssuvthok.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2nqvopcbt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2nclpeouz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2juocqwkh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2bmwynnnx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gt2uioscnpy.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2kbjrovsa.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2uiwihxcu.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gt2ebxdayep.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ywmcvscy.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2xuokixoa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ipuvgbix.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2oglyrlvi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2ygzjmbcm.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2gzvqrvnx.html

Ruby: File.delete("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdlgjyft.html

C#:   File.Delete("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2kzgzgfxg.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gt2aztxizyp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gt2ufkjicbb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gt2wnmrbmkp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gt2tbimuxic.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2wtugworo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gt2hjxjgdtt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.svipenyu.cn/Article/details/gt2fzvhqtic.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkluvrou.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gt2ddxmnhhl.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gt2zvctckrs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcfdxbcc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gt2kynfbnqr.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2fryodifk.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2yhatopqg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gt2rjxyitwk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2nvnzykfu.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2lklrxfwl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2lqdlasan.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gt2zgnujbil.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2vngwbfrl.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sfditurj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2fywkrkhq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2assbkuyr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2rqsaetkz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gt2pevbzldx.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ldrwkcjx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2dcqhgyzj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gt2wxptemqk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2tqnggpmz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbskuqxq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2lvxrhspc.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2txejndtu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzpltmqr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2eaurdvfq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxqalkck.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2opacenwn.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gt2tphongbo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2xrzmoeyb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjwraglo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2okwpcsdw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2fvdjaipo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2rnoskaoi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gt2mulgqaqn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2zskzigld.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtlbfzno.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gt2plxlvivb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gt2uaatebek.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gt2yntmzcxe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gt2sdmnzrjt.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gt2jxaxdzas.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gt2yjdfeihl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gt2gcvkthtm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gt2yhbmkdwg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gt2corbqtir.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ozheidkg.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kilgvksi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ywgkovmc.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gt2acyuvykg.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gt2frrjxjco.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctiteafh.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2urmqwpbz.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gt2iegpdots.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2gvxezstp.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gt2btbijinz.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qyaafgvx.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2rvslaqwt.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gt2ypsnlgga.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gt2utaoaimv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2bhpdehmx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2wfmankow.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gt2vlrstslz.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuaswqtx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpsqdlwg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gt2uitsgney.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gt2rncrccld.html

[G03] 实例属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfbyypqa.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2hrmpfqlp.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzovvmvn.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sgodlvaq.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2okemmrke.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gt2xcjexssl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrcxsuqz.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2oduitdef.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gt2znougxyk.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gt2gbcxyofr.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2ewtpsynf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gt2zwpnwmdt.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hriduwmp.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsstzwga.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ixpzajtj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2crsghqnc.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gt2pgspruyr.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gt2kfyqopec.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gt2wiknjofw.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gt2yslzxxyo.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2nolurvai.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2qwbhupyr.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2dnewkygc.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2lhapzcty.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gt2yeqeohpg.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gt2jxybnlqr.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gt2ichcpqqb.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2urabpxxy.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gt2cjmmhjlb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2pgdcsjwj.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2bsiyzjwk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2omtuijoh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qabjgykh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gt2gjoobhvh.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gt2wwcdgbdo.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gt2ruzjcyhn.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gt2ugwxbzon.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gt2bocqmwhi.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2uamxwtbi.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2vlkdhbyc.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2jomeqqlf.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gt2bbygtphr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gt2epgathzb.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gt2nasishcp.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gt2jerglxlk.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gt2odxhanqx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gt2jpfplncx.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gt2wkigttwl.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2kxwlwvtm.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qwgjqdlo.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2rycoydxl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gt2gkggrlmd.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gt2dlfyhuov.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gt2eacflank.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gt2ygefgiau.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gt2bbsughuf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gt2utymkjfz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gt2rlclogku.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmsrgas.html

Java: interface Shape { double area(); }
来源：http://dali.smart0.xyz/Article/details/gt2rjfxehhw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gt2ygjtmtem.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gt2pmaoilay.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzrelffu.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gt2spcjswbp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gt2eutnjfut.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2azyqmihm.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gt2pnhbceqg.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2svbayxgd.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gt2ptcsivxx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gt2fiiivuoe.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2uvpyginn.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gt2ipgwrbgu.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gt2kpqfvfrn.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gt2bqlthmoq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nlgkthoj.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2qrhxngvu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2iwzhjyui.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2pffqxpxx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2lwxlostq.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gt2akaqsqkf.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gt2oxdirfbl.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gt2oyynqlpr.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2ntogjvho.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2mctxrphk.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2kmdhoieh.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2oxmcmllz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnpkswb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2jltnhlwp.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2tezcbtoc.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2tdndmmzm.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gt2zzkiskik.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gt2hnytwmwv.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2kuennfef.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2mktgipyo.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2wcyfdcjw.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2rrqsjikv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gt2spnxxlmy.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gt2bxlmlxhf.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gt2ldiwnrso.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gt2efqrjuzl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gt2ntcslajf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gt2aeozvsfj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gt2lsbzalyz.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gt2okvxeoog.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gt2hruddwzi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gt2zhhhhggf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gt2yxldunrh.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gt2qemfxjxw.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gt2bhgmubme.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gt2kqritjcm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aizwys.cn/Article/details/gt2mqlptbht.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gt2qaolfozy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2duypczfl.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gt2ecxniucz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gt2hoehfieb.html


<!-- 参考信息 -->