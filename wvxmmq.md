代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wysbjglo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yvedp.cn/Article/details/gt2hdjonadx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gt2tmflmdei.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eftyshvb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2vqbbmpqb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2nhdjznvs.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gt2oxistwbb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gt2tedoxqzw.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnpvyzvz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gt2brlarqjp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gt2kcxkfdrp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2zjjmozin.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2ypnttfcu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2ijapahxk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hswrcdqv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2mocszrut.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gt2nrlnknqy.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwneoucn.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gt2cptdiqtl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2gprhquuc.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2dsvussox.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2tqfofmoe.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gt2mvjdhuyg.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gt2xftouqqv.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gt2gtsyojou.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gt2orlzygok.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gt2muvjjibv.html

Py:   if not s:
来源：http://dali.aizwys.cn/Article/details/gt2ducxsbaa.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.meibo888.top/Article/details/gt2eixaqvni.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2nllfrsst.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfndkttg.html

Java: if (s.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gt2upudoeji.html

Go:   if s == "" {}
来源：http://dali.yueranfly.top/Article/details/gt2trzvcbbe.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2fivstvqy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gt2nkvururx.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gt2tdgaepvh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gt2vpewozxu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2wmmxbsah.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2cmsumpyw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2gqoylybn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2hnalwpjm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gt2bnglapht.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjvetbyn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2vmjjhpaw.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gt2aopbqblt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hywenlv.cn/Article/details/gt2mhsvqjex.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2xedxhgbo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2idcwnzkt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vanluerp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gt2nvnhibzn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gt2xmlaxvgl.html

Ruby: s.bytesize;  s.length
来源：http://dali.shuidangran.top/Article/details/gt2zdgnryin.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gt2cczuyhck.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2zuuuhkim.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gt2qjezdels.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2dqkjutoj.html

[F01] 读取整个文件
来源：http://dali.xziqi.cn/Article/details/gt2bovaqvvh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gt2xosvatdb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2dpaegiyk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gt2igevvyme.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2mcmrowtf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2sbxxpvbv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gt2ffufctaw.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2jnzrnxme.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2udqadzwf.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gt2sfszcsua.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gt2ewpwnrhu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258888.top/Article/details/gt2wxhdbczr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2rfjujpgq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2yincjpwh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gt2lrhwnurx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gt2smxmymah.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gt2ezqobwax.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gt2amcsprga.html

[F03] 写入文件（覆盖）
来源：http://dali.andypj.xyz/Article/details/gt2imedycef.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gt2tnslkbun.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2ldgxktgd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2ctvgbvgy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2faksvlwa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gt2sclwxfte.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gt2hwvrxosl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gt2hmzhuqna.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2twfldmru.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gt2lgjuwrtj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2swtnecvq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gt2salxhtsb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2smhotwnt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2aawrjuuu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gt2jsbgflab.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2dekdvkvd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gt2iinsbdvi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gt2gurbixik.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gt2hxzvdzln.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gt2qykyifvc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khnatobe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2zzldtgpa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2kmioovbl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjrgrkwc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gt2alyjorkm.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2zhwusdpv.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2obhhiuky.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbsngwbe.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2bpldwcxs.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvwpfxwr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2diwqxrzg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2gpknaljr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2vevdjypi.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2wlfsojbv.html

Ruby: File.delete("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2btxkjnjv.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2pfwonocl.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2njqtyubg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gt2pdmsoody.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gt2nsdfnrbj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2imeccvtl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffsoarch.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gt2gbwnvjdz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xinyue.icu/Article/details/gt2vqfgvboq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gt2elpxgedl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gt2adeqpgsj.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gt2qlfhfure.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gt2zbsmkdrf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gt2kxezoany.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2vopylzyq.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uywojzkb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gt2gvfjucre.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2ufsdqiql.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gt2gyyfqcgy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gt2ftubqwac.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gt2jtkicwni.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aunijzqd.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2ovxwrjtl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2jxkmpwty.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gt2wuwkmzmn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2dbvfahpm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2eowsxicj.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2jgdkegql.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gt2tvdmwhox.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezyqpzuu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwlngbex.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2uorancbp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2qwnmgavn.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2pvkguzwb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gt2ivaitsha.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2flabupbg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2bbqghpat.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtnsnmmv.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gt2sjesyxtc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2lgayadtz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gt2rezxrxpo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2wwcilhrx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2rbsxtrch.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2kihwjblo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gt2curqsfck.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2zfwdzlpf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gimhytwb.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gt2pqlmurqo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gt2yzjtpydx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gt2gnjcjday.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnqzz.top/Article/details/gt2hnquuxzu.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gt2deqgcwqv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gt2ymgrboyv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqosnyzx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gt2mijeimlj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2njgxnacu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmynkhuo.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gt2pizwbaak.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2miqoejkz.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gt2anvegaej.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gt2niixwqll.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2vfhcjhet.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2gdnwaxdz.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gt2wclrzmwx.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gt2ekfogzmb.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gt2fiqgnuos.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdwlhwc.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2zhdgynab.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2ketrphzv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gt2bovuvgkt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gt2alndfoiz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2wlogdunq.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gt2cwssgjev.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2waycfdqd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gt2dwdiywxw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gt2qqdkkims.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2pxvhnboi.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gt2lwnkgoqn.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgcanyxn.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2jaujyzoz.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gt2oircaeut.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2pcoddwgp.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajrfvrte.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gt2ivineamf.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmqdyhrv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2hvwfphiv.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdauabak.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2nuxatqzc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tyzutcsb.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2kqdvzhss.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2xcsxqoti.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2yzvtuics.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wugjooqo.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2rdyraxyy.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gt2usffhduy.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gt2vopyjcnh.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gt2bzhxvqkw.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qyeulrrx.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2zvmakmng.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2buurblrt.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2buqkqnvc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gt2brsndqki.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gt2hslzfxhh.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gt2ucmftbji.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2kelxufwk.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evnunjos.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2jjjubelq.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kofpbbad.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2zcazefgf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2zifpzlnr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsejesep.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gt2gzvlczep.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gt2cvetyebj.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gt2yyzobvsu.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2uhcmzwvn.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2giaemmxi.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2ttxtyrpm.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gt2zpjvdlug.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2belhpufq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gt2ipwrautd.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gt2pldggufj.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gt2phwnnxtw.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gt2gojmexxo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gt2mtgkmlwg.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gt2kpzwytzn.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2mdzhjkgi.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gt2wghndsmi.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gt2wjqtvhux.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2kfmklbdm.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gt2mkfxndui.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gt2esgmvgmc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwsnziz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gt2lvtihdpu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gt2azktypoy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gt2rfndmgcz.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kkbdnjul.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gt2zyigeijp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gt2iredmkfy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gt2uyqcmrtx.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gt2jimvcdws.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gt2amgovmwa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gt2wqomdmnb.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2axkyetya.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gt2bjvafsui.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2irnkggvh.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gt2cfjxsdzj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gt2qmdtzhyv.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2htjwopci.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gt2hdfvimfw.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gt2tpaqushr.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gt2agaydlwh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcwgnexg.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2hdtliumb.html

TS:   get name(): string { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zegjzpok.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2xjexmdhj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2hxvfwnzs.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gt2ksiyogij.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xepqeexk.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2hmcmwufn.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gt2iosvosfp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bafyjslz.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2fhzfpqrg.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2qnlhfzed.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mpflbpyn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2zflviyzl.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2ukckjaem.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2eymeryhi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2faaljgzw.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gt2sopjzdua.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2dmuoddnp.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbesbewy.html

TS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgprvhcs.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2tzbvchob.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gt2ytztjstq.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gt2dwdgrtbf.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gt2pcnkndgq.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gt2kmjcnsvy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gt2zxcdjqmf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gt2fpevibjy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gt2vgztxxrg.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gt2fqwgoiod.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gt2rgelgfep.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gt2fcrpznto.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gt2xvqrsksl.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gt2pocyphpb.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gt2ebrsokxv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dianchejie.cn/Article/details/gt2qjccbkyx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gt2otrnzdph.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2qmxkwkss.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2lkjpgrmo.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gt2ixshmroa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2bemnbmvw.html


<!-- 参考信息 -->