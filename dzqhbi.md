代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gtecjfasza.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gtpkxlxwru.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtbhdthrlb.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gtmsfgdmki.html

PHP:  number_format(1234567);
来源：http://dali.jqgfzy.top/Article/details/gtytafagfw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtjrjrljgc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldkokzem.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtdicpvtej.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtgmqeoeky.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gtcbxxcmqb.html

C#:   1234567.ToString("N0")
来源：http://dali.ydzc1.top/Article/details/gtznlglnuk.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gtubkgvoim.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gtmyadvvih.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yvedp.cn/Article/details/gtvecnjhmq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtsnykaesk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtgqiaeqyu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gtnrakvxmx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gttfhdsdft.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtbyrhttpv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gtsmgapzht.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gtyvumwyby.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gtgvghejwg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gthtbnvtdp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxyjaobw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtrxztuegc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtgszjaayf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ybcxt.top/Article/details/gthoxnhnmq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtcfsoadjd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtyibibqzw.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtnhcymmsw.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gtynrwjxmu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gtumjonogn.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtslvgzpwd.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gtlfxmvigz.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtkkrqbump.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxuanxn.top/Article/details/gtdejlgvqg.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gtdxvubpiq.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gtfbgzqmaj.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtzliqxumd.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gtgxbpsxhe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gtjbbmnnhy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gtutoanblt.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gtgfqjpiru.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtvgiafweg.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtbeefjqyq.html

Ruby: if s.empty?
来源：http://dali.yanxiufei.cn/Article/details/gtgonrfcqv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gtedzwznaa.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtnnprfhau.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtmidpnpzs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtrqluxkii.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtrhomuvuq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtfgvkxzah.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtsxxwwreg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtyaghdvzz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtblviynvc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtdkeaajzx.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gtfxdkmriu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtmyozbrsh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtrsvlqgft.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtbodhxmvi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtaroohssz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gtxtpwyhea.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjngddkk.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqtlzetf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtgylalzsu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlqxlhwpw.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtvwvjrhab.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtiqpwcdtn.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gtvzbhukly.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shzxlz.cn/Article/details/gtgaknbdks.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gthelrgmvy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gtzdekzwsl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtuxsimskh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtgsqelffh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gtllweegef.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtjetzjmuy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtgydogrqx.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gtcgcjrazv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gtlzrlzwhv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiljopapr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxxkwgzb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtfiqwumqp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtfuthpqqn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gtkccrryym.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gtcyyhistg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gthqbvfgqq.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtrcdkbncb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gtjxtlcipm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtojyxmkzj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtojputhdo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtnpoalber.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gtdtydxlyq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtanrxspns.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtadwtthdh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtezydwxqy.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcgxbsfq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gtxvgqrttf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhengqikj.top/Article/details/gtowaietva.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtlktamtvc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtgvajuyej.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtevezieti.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtijjdbjmx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gtplzgdkfn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gtbfoxzzky.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtngoblpfn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtczvtneus.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtawcsakln.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtnuhatrte.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gttjqtjmev.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtzovvcfph.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gteizdphsq.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqlsxcyya.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbpfbfdc.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtvtkzvelp.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtfeswuqmf.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtmvaqoxmh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtfdjkxcfd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtcmohesim.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gttqxsiybq.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtpodsvzha.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtfwhxekvr.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gthpoxuoqk.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtcnddeurm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtpdvqvbjx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gtqjjiyhra.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtpddyogpq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtmcgqbmet.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gtmveqvpxc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gtyysvyndu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtfzhadveo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtzdmfehbo.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtxkzpbcjf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gtmqmsfsad.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrmfdqct.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtbmwulapo.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtztjskmrn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvzcsvvv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gtfrvctnpv.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtdrouhcbm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtyssxovco.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtejmenlhb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtvkanoqrz.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtmsrnpfml.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtncbrlbnh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtoqreqqia.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtrtzxiclz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzdmgpfw.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtukbxaaqo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtkzzado.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtwaknpjyg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtezttxoyp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtqeoxmrxv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtvgqomrki.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gttkesdpiy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtohuymrda.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtogjkqtes.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtolrvaztz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutcafjsm.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gtxwbralck.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtmdlnzmeo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtxudkadld.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtndzlwplz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtriitkasy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtbgcrakix.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtkjygpksc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtybwulwie.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtpizylkou.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gttdlmzemy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yongpay.top/Article/details/gtnplvgygl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtqaevoguz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gtlmjbhtso.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtzstgxexn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtffydorys.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gtngxhzfjb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtutirpecp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gtiqcwvzhy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtcmjdwoev.html

G. 面向对象
来源：http://dali.daria6918.cn/Article/details/gtysajabno.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfikxaymh.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gtfrmpbedg.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtxevcdibu.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtuhoahgzt.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtgoaoaift.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtrjlzzwlg.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gtteuzoihm.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gtguvzxjxq.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtiwmzqsdv.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtdweuegva.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gtepxghkcy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gtizipuhzb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gtgbwgltvs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtazonfoup.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtgrmutmtb.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtklrsblgs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtofyzklfo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gtlqgpuqas.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gttlkuwmcf.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtennpijzu.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtwcqkoktq.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gtvtmxgxkn.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gtvuubjifk.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtrjydsuqm.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtheftlraq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gttcsvtipw.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gtbweqokqh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtofxuogaq.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gtegxjeefq.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtxfypumxr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtrukhrpkr.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthviqoijd.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtxltphvlo.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtgcffglgl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtfegcqubd.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtowwvvdys.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtkqbylzkb.html

[G05] 继承
来源：http://dali.316326.xyz/Article/details/gtvejbmcop.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gtsywbjvxp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtnssxlylc.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrtztbsm.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtjysicxsn.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtzcxiwoeb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gtejdvmond.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gtpodqpoua.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrbtvhddw.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gtsmfnqdvc.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gtpzviadod.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtizgaurfl.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtmuufltxe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtfvvzvhvf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtekeinobk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtvbakrpmd.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gtxdzhxucu.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gthmmjscoi.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gtsycxwhea.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtccwbkgil.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtizgxnwlw.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtctsfkplb.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtwviefqxa.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtkejnqtmm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gtstegstfe.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gthayjhatb.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtexbxckuf.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gtnqprzwkj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gtbwvlptpw.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gtwimuacbg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtigbapwqn.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtbbqoxlwb.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtshxwqvsg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtdaowqtfy.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtaxvdgews.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtrhnkbyoh.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gthngjjuzj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gtaudauklt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gtyeueqwft.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gtjhinmfcg.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtuosyjujc.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtfuorstsh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtskimocgt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtmqqpbxfd.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gttijhgswv.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gtlhnbmzdo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtelnfpdxf.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtzxolgxpr.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gthkcppkjy.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtazsespjj.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtjagmwesh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtirapblye.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtzqzkgvro.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklxxqaqd.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtgicajuwh.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gtsgfnfzqc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtindsprvn.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtsldvyyon.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtraaobxww.html

Java: public String getName() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtimpbxokk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtsdszjfxx.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtsyzekisd.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtydjtekoi.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtibqmmaup.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtxnytoewy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtthhwfhqe.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtidnshjkd.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtegrnsjki.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtwwosdypr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtcjobvkao.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtvfnljvfu.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gtlbctfbxh.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtazrreztw.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gtmqydeziy.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtecszggnm.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gthftfmzjs.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtuhiattng.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtmjnfikub.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gtxcocdcga.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gtsmhgrwhj.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gtehicjrru.html

[G14] 数据类 / record
来源：http://dali.hammf.cn/Article/details/gtahckkxku.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gthvcdokpn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtmgmrucfs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtbynsadkl.html


<!-- 参考信息 -->