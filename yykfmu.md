代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.birdmap.top/Article/details/gtjuxgfety.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtbmvlqsop.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtaigahuah.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gttvwklcsa.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gtcwzkfixf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtuyjuogbp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gtnunyonmj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtvnatyqug.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtmdgvfmlq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtgkwznamx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gtuupinvps.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtmodcgxav.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gtggsiswsj.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gtxblspjsh.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtgddorwkk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gzhubu.top/Article/details/gtlaovywut.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtkbkfzvve.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtgkgesxqj.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gtoghkuvpp.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtdwkfrlfm.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gtnxctvabb.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtmrgkhsun.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gtkjsnazhj.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gtntbbsknf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtmeadmwrh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gtpqimtqms.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccibibzn.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtyqwkewls.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkueqcbtc.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gtzftdgtqw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258.top/Article/details/gtkpjfrhao.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gtghogefen.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhoulong.xyz/Article/details/gthmljenfg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtizvutkcw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtofciczls.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtsunabiws.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtlzeshwut.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtpcjkzuyl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtvvepnoyr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtzgrvxzcw.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtjeweuinj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gtajlkeegc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtpdzkmxjz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtjxqjhhko.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtrwhwkmeq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gtkfvuuefx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnhllytu.html

Ruby: s.bytesize;  s.length
来源：http://dali.yueranfly.top/Article/details/gtkryqpxwa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtzxjuqwgo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdvrvbchh.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gtqvakntua.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtklragknk.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gtkuazknwg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ivvv.top/Article/details/gtyslecqjg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtydydqkzq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gtwigxrhjy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtmpwoxhlt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtmrtgkusv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gtoppqrhmg.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtyhydophn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtwirpighd.html

[F02] 逐行读取文件
来源：http://dali.xinyue.icu/Article/details/gtquduuave.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gttgrlulhd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtuarfdfov.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtaqipurzw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtkwwhfcoi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtpfbdombo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gtnhqdfzfk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gtitshdvht.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gtaeccjckp.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gtxtxavmyw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlslhoen.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtdkhhnopz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtqjdjkknu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtqybudvfn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtwvdhojip.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtivcyznab.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gtsrucfjbt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtkkwcvbeg.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gtljeecmfn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtpjvrxlpp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gtcxxnkiit.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfoaelzm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtvqaypzrd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyoqrwvt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gteyofqehs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwgdrelu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gtrldvfakp.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtehdedape.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gtkllnnxlj.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtkfdslizm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwkynjvia.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnlkmprf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtsjgugchp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gtzunyyoik.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtsprueaql.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gtshlrszum.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gtdnklzspa.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdreleorz.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gtzndlhhye.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtfgmmsnwf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtgkcisfmj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtpednjrkx.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtenspvatn.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtpxnrvlnh.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtibiyqkpe.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtppbaxvsu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtoovoxhqc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gtpjzpppty.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtzzqiyvpn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtxrtuhgyt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gtenewsilf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gtpqqdvzfg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtyshvzkas.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtdvxbtjof.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gtalbxqntz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtbupyneqt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gtldhumobx.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtfeswjxzc.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtlpoowdwk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtrbfqfqym.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtcldwbapo.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gtsisrfkwc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gtksxscpaf.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gthwwqvzot.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtywsjobnu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gthvynyujb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtbsmpliaz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnntrpwi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrprevpmz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtiyplwerh.html

Ruby: File.size("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtsguxjvig.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gtuaanchhf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gtrcxzgknj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtlyxglnpa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daria6918.cn/Article/details/gtdldihtvh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtqspbcill.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtqjlvuotk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gtqokqzpnf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtkprvgvwr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtlhbhnhcb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjwvfstgg.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtwhmjruyq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtpeznjoak.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtxzlktnbq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtcfjgcmli.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtfnfavcms.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmolfsku.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gthcaabfow.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtzuhoyoeb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtkqkixcyv.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtviqmoiyn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtixxvutlr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gtlvpdlypy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtmuxuvcxk.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtjqfzcmvy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmrfencj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gtgwrbvogb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtyrbhgvhu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gtoskwpjqq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtpdvhdjdz.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtcmtcfuxz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwzprpikl.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gtxgyaicmw.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gtkwdccocv.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gteqaawzla.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtwgluvkkr.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtavnfyniq.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtummedxvc.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gthibyjbun.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtmrnqiadz.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtzgzyxxpp.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gtyhlavmfz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gtsrmijphv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gtgppcmzir.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtpvfessis.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtytomcaga.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtsbjcovhx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gtlrfhismd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gtpxlgihpf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gtbglvueht.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtvnulqnpe.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gtatzwrwvg.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtvhccfzsn.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtsrjgbafn.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtoxhzozvq.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gthghaqzlq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtohftckhw.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtahvjtefd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtbjavitps.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtaiswjcdu.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtpthzgfcq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gthpfuqolj.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtbyjedkqw.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gthbqlqcec.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtqdllxzma.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtjgswtenp.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfqlrjbr.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtpsumhncc.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gthyuyyyte.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gtjzxlsnqn.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtcvjoefqa.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtzklylqen.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtdcltigdw.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtwwcamluo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gtlwdupfap.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtcbifgfco.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtbvadmbud.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtabdfbzdd.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gtsxhtiotq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrnzsqna.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtkkvtsmly.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtxaeibjls.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gttqbqqmkw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhdjetpg.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gtmnntbymf.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gtjrjvjwmk.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gttrzisahc.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtriefznap.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gtiucihvkc.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtmkrbiulf.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtxzoizpra.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfhrghym.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gtnhrcxghv.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gtkjixxxqo.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtuvdexwbw.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gtbtsmuqnb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtogchnpak.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gtnionejel.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtrkaxvcse.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtntnefsbi.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtcvbrwysa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtwkmsvtrz.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtumkiupad.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtdpfhnyaj.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtdmpscnua.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gtqujyopur.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvyqgmzq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtkjufgmsd.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtbmzqhmyx.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdzevpgtk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gterxubvsi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtdtmhhulg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqigfyza.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwphrbkd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gtmwwwmsyf.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gttwvcesjy.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gtzhsflzib.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtzzfajzjn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtvbdolriq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gtbzuqdlfj.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtiutedqki.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtutjxktct.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gtqpuabbig.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gtmgzcdxtb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtygktpbwe.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gttjwdhdee.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxouagbx.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtktudiuwr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtskjfswiu.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtjpakkadz.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtbolasvhu.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gtmtqqyvem.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtzsoggcod.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtfewcuvhv.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtpcscprez.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtejszgbya.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtxrgexipd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gthamynncx.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtnhfwkony.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtbmuvkpcw.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gtcxuqrxer.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtazkhwlxm.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtdvzsznhf.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gthdqpezrw.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtqhqfuqfr.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gttzvryvzs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtdiehrapp.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gtfaylwtmb.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gtcaoajyag.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtqxqchajv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.havefunace.top/Article/details/gtbaqrapve.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtgdhtismr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gtgjsejvtt.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gthpqljary.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtshqkbxrn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gtqfqzkxfy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtgadjbssz.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtnfvnhyim.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gtvhdubxie.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gtphhhfnln.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtjfqhlqwj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxykuqmz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtaigwaphu.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtrunvmidi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtpgquqqjd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gtctxynlbp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtqexvgstj.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxinkj.top/Article/details/gtvtdltfcs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtissafalt.html


<!-- 参考信息 -->