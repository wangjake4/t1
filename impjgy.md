代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gtgoavrwxx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlgdcjzg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtdujyecnb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihbnplah.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gtkhgabboz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gtkogfpxqf.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtmovgvqjs.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yanxiufei.cn/Article/details/gtrsukwyay.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gtuwvhcvkt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gthklgfdnk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yangfankeji.com/Article/details/gtldtyujrc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtsvoxhxvv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwtetnyz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtblgzfpie.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtuytuwjiv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hammf.cn/Article/details/gtbkeghzgs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtqbeiqgjd.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtemvytfyh.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gtokutdkef.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gtqlbocbwh.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtzlinkhzf.html

TS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtzmmvlapz.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gtzfnkwbpb.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigufen.top/Article/details/gtjvbvdfkt.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gtrkomxcjn.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gtrtygufih.html

[E20] 判断字符串是否为空
来源：http://dali.hammf.cn/Article/details/gtcedtlrqx.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gtxcnawqct.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gtljuwjiws.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gtryzdganq.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gtuinthsds.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtwepbvhid.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gtvcdnhsgb.html

Ruby: if s.empty?
来源：http://dali.ydzc1.top/Article/details/gtriloooku.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqopyzrcl.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gtohjcjdpd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtirqctdcu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtkadfdjly.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtgtrgxvqn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtuygihvrz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtkxcwmlfc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtlnysyveu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtcuidlbdp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtsieafixi.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gttbyzkwzp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gtwqcalrfi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtegktqjnu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtbifzgvmq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtqrqbwqne.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gthoodurhm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtcilatnwg.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtwfugcrxd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtprijfqvb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyapvmpi.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gteanjicgu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdqyomwhk.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gthejryhgu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zdqjudy.top/Article/details/gtorunftnk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtufjzcgev.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gtoqayoreb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxkmbqvj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtiyrmgugr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gtrqpanmzx.html

Ruby: File.read("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwswnovgq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtcyyokasb.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtimdbmbvu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cqqwz.cn/Article/details/gtiyctwkre.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtkiyepwyj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtmodwlpue.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtdjstmbpn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtwkmipcjb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gtqwymckfh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gtiaagbsbf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtqgwjhsps.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxaulumqk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gtoxvpmyrc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtedteglor.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtbmikjywm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtpeqdpgxw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gtgemjjmmq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gttlsxyycg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtrkcwhtpd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtiljviqql.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gtotryilol.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gtdnsubqme.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gtyrljaxtc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtfibdnqfh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtcybcfckf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cashguo.top/Article/details/gtefpgykdt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtgdkwdhyv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gtdedvwiwi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgfzy.top/Article/details/gtyzctgczm.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtmwncyelv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gtyeswiuwf.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtlxbpkjkx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtuydnwyiv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtfomrqewx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtwhyocwcr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gtidotmphy.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtkmfkdhbi.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gttjxkjhen.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkitomvk.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkqowfff.html

PHP:  unlink("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtampwhdcg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtrptufzdx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvwgfggnp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gttcpibtut.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtlhcxtsjd.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gteohnffie.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtbejkgenf.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gtycnrocen.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtwcjppa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gtvappmdzf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtfcqqllhu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtqnkoiztj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtvontjwbt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gtizxnuoav.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gtdwsdidun.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtgqlmezgn.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gtnpyakqkr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtlxytgpcs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gteotvldom.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcamuzzgy.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtwryephxv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtdhxzdnep.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gtodzcdzdx.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gttxslzrrg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gtzzgnadgm.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutsruwgy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtqzswvhwa.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtxungedti.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtiyegyhgn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtosugzmyp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtjgdnczyl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gtsgnlslee.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtepupmbhl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gtftjnyfnh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gtoncvxyqr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtrixnxpsi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtecqnmgsv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtxcppecdq.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtnpcqbryy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtkrazixrz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtoplpgsbh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtkevcyyie.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtdlnxajax.html

[F11] 复制与移动文件
来源：http://dali.jinqigufen.top/Article/details/gtaqnhvgyx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtlqoqgkdv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtmwqibjzm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtnhuwqmwl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtzytbrkmo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtzxpurora.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtnxykshrk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtqvzimwaz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gtanhgzwif.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gtptjvoumw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gtaqorpbti.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gteksvumwo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gtnsqjnvls.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtiiovikcr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gtzshiyccg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtczokbcqg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtidsupshp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gtbxexxqta.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuzhdqqzm.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtghdvamqv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxjbxsmrf.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gtythfzhxv.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtulauxgyx.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtelochstk.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtmtdydllh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gtdtdaohma.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gtjerrcvxu.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gttiizuang.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gtofiatgou.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtjizeahjq.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsavaldsv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gtvnbpczht.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtgymskapt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtetqyhqcj.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtvtxbjcwh.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuevrjvlk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gtxlgctaim.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gtotdhbwlq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtygyuhegb.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gtfqmoywbp.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtqfbcfwek.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gtxnamuuaz.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtljjpmtbs.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtzwyxzkxh.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gtnkzdeyof.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gtivqxaoqk.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gtoqpazjng.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtptwfrcuv.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtfonvzuhz.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtcwcvivwg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtbsiadost.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtoeentxxc.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtwywbonap.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtxwirtk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtyftitnmw.html

Ruby: def greet; @name; end
来源：http://dali.xinyue.icu/Article/details/gtujzwhhxl.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtesxepftm.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gtpnuognfe.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtgaotuvdb.html

PHP:  class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtlthpicvd.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtsvvjafkh.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtbyeguylk.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtkrtspupc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikpgehfy.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtxeodjobe.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gtroaxkqev.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtuobflguc.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtjcqmctmo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvtgtafz.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtfuhyjhqw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtxvrjciol.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtyidsnwcq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtwhzeubeq.html

Ruby: def greet; "admin"; end
来源：http://dali.sxryk.cn/Article/details/gtrdrloeoh.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gthmsqwipr.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gtoljjfeyn.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtgwroekvz.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtpoibrygs.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtqkpdnlrk.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtbkgvhdgl.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtqcpeylyi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtmcxlkqei.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gtzocxdxql.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsasywbtw.html

[G08] 静态方法与属性
来源：http://dali.jianghu66.top/Article/details/gteddenoma.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtrzgrmztx.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gttkjgbiaa.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjowokdj.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gtrmqzpdgy.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbvcfhztk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gtbnmqqyie.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtkawiueig.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gthbkeabsw.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gtkimtrial.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtyqmcksom.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtsxsedhqy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtqkvjaeom.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gtprbgszhy.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtzowchqnz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gotoacloud.top/Article/details/gthylebhil.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtghbiklpo.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtsicsovyj.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtxcijzaao.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gtgganrsyb.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtirgqszfn.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtsgwjzmfr.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtohaedodc.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtrqnodimf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gtmuesvlkz.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtlyfiibwc.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtlscaasik.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gtkgguuulb.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gtgoyafwmo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtocqtjxsr.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtimtaatnp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtelobqiat.html

Java: public String getName() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtyllvsouc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gthugazfpv.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtskakgsyx.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtdobdysdi.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtyvsejuzh.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtnpihhdxh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtnqbwpetu.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtgolgblao.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtprygflaz.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtfbwxyekm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtcvowaxpx.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtlsfwjibn.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtlmlzomve.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gteeuzpiod.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gtqbzplogl.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtkntgbcny.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtarfmqbfe.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtaazfcnmz.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtndufxsjf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gtlgiqgclt.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtzmqeshma.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gtuqaexkql.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmmbmhak.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gtlopbfzts.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gthvghhvei.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.mhx1999.top/Article/details/gtcrulbdgz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gtrivujuau.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gtefvbtqlu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.bjfxy.top/Article/details/gtwflbrrkh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gtibjxsspo.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtlotndiuf.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gtdihhydor.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gtpjvzfmhn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzxmslagz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gtrgigrfey.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtrzufgbuw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtpsrldiyw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtedptwwqj.html


<!-- 参考信息 -->