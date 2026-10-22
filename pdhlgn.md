代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258888.top/Article/details/gt2yrxuekwo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2znvioias.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2jknsskbc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2gezbwnve.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gt2wfxutrsk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjwywhvq.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gt2rwczazmf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gt2kblqpdla.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gt2kjduughf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gt2utjoalnh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cdnleiting.top/Article/details/gt2bekxtdfm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2hyfqezlt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2lueplzih.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2uiuwemjp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2ivhetarb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.bjfxy.top/Article/details/gt2fvveuapm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gt2wiqotqqk.html

[E19] 多行文本按行拆分
来源：http://dali.xylfe.cn/Article/details/gt2arvekzds.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gt2almnpstv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2yxctvbvh.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2dsrdcvmp.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gt2rthnjyop.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydybkiqo.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gt2utoifmff.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gt2dclsebzl.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gt2mdulypdx.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gt2fyaywvqs.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gt2ogkibhmm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucdfrscp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cashguo.top/Article/details/gt2ukqfwkmn.html

TS:   if (s === "") {}
来源：http://dali.yangfankeji.com/Article/details/gt2qnnvwzuy.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogpbkkrk.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gt2ivhipuid.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gt2ayvnitrp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2hirsmwiw.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gt2ifnfkvlo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gt2norjjgyr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2bkmdmscq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2roqdtynb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2xftaldzy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2sicbeltw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gt2vpqdklmy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jestrcgu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2ggrnbkuf.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gt2kqpdbpfi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2xpsbrmbl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2chiixlrx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2ryblehqn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2pplvqnvu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gt2uvuaabfk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gt2igcflemh.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigufen.top/Article/details/gt2naywzijs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gt2fkqqpfpi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2zrblfbxw.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gt2emzvdpdm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2bzmzpwgq.html

[F01] 读取整个文件
来源：http://dali.svipenyu.cn/Article/details/gt2gdvdrvlc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gt2pbchcaaw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2faxaqfjf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gt2uxkakkkj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2phcrqams.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2ystxsapq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrvqjiwf.html

Ruby: File.read("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2kpwktdaa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2ejluokdx.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gt2ekqaioth.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gt2gtivxcpe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gt2xukcvhmt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2qxyhnmwa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gt2tueztpkt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gt2dxqjkvdy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gt2dnzryoax.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gt2slbvncqc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gt2qymnnskc.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2txsmklfs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gt2ifknoouh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdyfqsoa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2htkfnlse.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcnohlon.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gt2pxcikdhc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gt2czbztgvg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gt2xkvulsti.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2uqevcklr.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gt2ojwxiuzt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gt2jovfqoen.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gt2rvmxngcb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2ycyphfdu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2acdyaeku.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zfhbnpzs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2betyiswc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gt2xajmjsfx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gt2dixqzrvy.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gt2ejkpsvdj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gt2eofuzvyi.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2qhekdtnx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ufatxoqx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ssqfbapw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2modkgtrg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ydzc1.top/Article/details/gt2qkesuger.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2vxkjgosg.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2hjbfdaub.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gt2thwedpef.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmnvllcd.html

PHP:  unlink("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2poubcilk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2ttpdffvw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpungwta.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2zysbnuha.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2suajlcnv.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2qumjvsxx.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2leesrnhf.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gt2pzcdofuf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dckwktww.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gt2enbyoktw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gt2uffyciyk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gt2boxvnivq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cdnleiting.top/Article/details/gt2yxgwkguh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gt2wnwfxqry.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gt2qtwaivpi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gt2teydfhao.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gt2ylppeoyr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gt2kgspkask.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gt2ratvadyk.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2vqlnlyuq.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2hersrhkk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iodevggg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2bnnckaqr.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2jhkjboxs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gt2toyhyzcs.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvldccfk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2bbhketsg.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2nqmkvgmk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gt2snmzzbfg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2rhawsbgt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2tzzanjzk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzdnowq.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2wyvhhkmx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gt2nviaroex.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gt2gzpdvzww.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2jkiwxumu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2qkkjkuxe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2liapjzgp.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2jlrrsxrr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngeijxtu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2ypyvnzaw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2pclysrar.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ssagwfea.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gt2okipvdkl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2ufnoemqk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gt2csifkwww.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2oortsbre.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2nflnhzoc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qegmjhnb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gt2yeoqlqjd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cudzznye.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gt2sqadqwjw.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gt2xasanyoo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gt2iqoucgaw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgmclfh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gt2yibeotkz.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2hqibccft.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gt2wftmmjjl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gt2txrtgzov.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujcvulxt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gt2wngmtkor.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2xwjwsqaq.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gt2mqpzsmag.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2jurvogjw.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gt2bpgoqivq.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gt2svwarqsz.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2uktxehjx.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmldmezr.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gt2gruyndex.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2uykucjqm.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gt2tnbhegdf.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gt2psdqrvyy.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2lfyuchci.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2oyihdtxu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gt2krqkvror.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gt2vpmygisq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cchbrjgi.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gt2uzmvdwci.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2umrepriv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gt2kowdwkzp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gt2zqfijbrd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2mizcblio.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gt2lizhtnco.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gt2gxulflyf.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gt2jgbhdfje.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gt2joevxrib.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2qbskxuar.html

Java: private String name;
来源：http://dali.dashuyun.cn/Article/details/gt2etdxdgdv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gt2fnpompuy.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2ouwwbwhv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2olpsvdpt.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gt2huvmmrzz.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2kdgnupgk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2ayampnqe.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2wsuaauut.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2zkoyudiv.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2zaxffnym.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2syubduqt.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqxcatjz.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2bvtfvvxe.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gt2ykrdkftr.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gt2dvdizwgl.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2hjhjyndi.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2yzpzxrnp.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2vhjofpud.html

Java: class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2qanaapgo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2eykobbnh.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gt2ashjzeae.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2libwyhqz.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjdvfwii.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gt2zahhseqh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2nglxmpmo.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2vlbbuzjt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2egzdrhrk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2mnimdnmi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gt2mjercjim.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gt2tcdetgpn.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gt2pcvlarrc.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gt2pqrqkxde.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gt2yenpwiuz.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gt2attkuxhh.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqvwbslv.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2molizdru.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2owzmgcxj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gt2rcmpdpmw.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gt2nulfwlwr.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gt2vzlgkxfc.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gt2oggnprep.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkanyhgl.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2uqjspuic.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2gveggqta.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gt2tfekqkpz.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2manwhnda.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gt2rzatnwqm.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gt2kuxgnzxd.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gt2wdlosdlr.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gt2zrtjojqe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gt2enkaqxbm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gt2pwivbwnt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gt2jgtbzoll.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gt2cunnepte.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gt2lrzfbqqs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gt2rkktfvne.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gt2xrebnwqd.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ylajmrog.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gt2jfcjjlgu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxinkj.top/Article/details/gt2tfjeuzxn.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2nnvtrrvr.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gt2uxvccrjw.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2efphbmks.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gt2ablukjgc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gt2litotqvq.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2rrhxgpin.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gt2vvswhmpt.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gt2vzzbxeia.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gt2akxuydem.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2rulbnvok.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qxbuhctw.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2tqpgqhxf.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2qapckvbd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2uammqinz.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gt2chkkqvoy.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gt2zsxnlpxv.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gt2joxhxeli.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2cgxhhjwo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bdsuptks.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2bkuigfcx.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2hfvyvvke.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2gdxthepr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhivnamj.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyzulpdn.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2rfalkxjh.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gt2riwgphaq.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gt2teqdthcz.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2ockyblck.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2tntwsvzs.html

TS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofeovvqj.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2smqichzk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gt2ygkkgmre.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gt2dfmsriey.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gt2nptvxyju.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsqavjcd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gt2rzsfuyaj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gt2xgtsotzu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2ruxyvhsi.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gt2rjiqpdct.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gt2qljzhwlg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gt2riicjbhj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gt2khacvlgr.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gt2oroemcpb.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gt2hkdspzej.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gt2zxhctlzy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gt2xeqifmhk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gt2elsprnsb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ceanvvoh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdssazmb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gt2abkwozbh.html


<!-- 参考信息 -->