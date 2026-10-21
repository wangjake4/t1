代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtpqcwybdp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtyceszzjt.html

Java: s.lines().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtfojivtvi.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtnbrwhasz.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gtporfrmcj.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gtmpeaorpt.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gtepesajhe.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtawwtuyny.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gtxydaeozm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtysvvodaw.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gtullktonw.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfucsybca.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtpvyedtjp.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gttdmnszgs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gtptpbdpnb.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gthnhjxqlt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aizwys.cn/Article/details/gtcqqvdxbv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfutzewm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtofgqtqvk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtgshvdomr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtyxrbihpg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gtyjodlrjg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtxrtzpkvs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtowxnxvqh.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gtktbnrfmq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtrqdyngmi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtnvixyjhc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtksbdnhrr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtjbuzjivn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtmnseihzn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gtkquxchkn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtbcnvkirv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtfxkrtfew.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwycgnouy.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gttpbsunhm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttjrbndye.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gtsezvzaot.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtmoufvmok.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtysarghqo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gtxsknwdni.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtejgkfdkj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtwcgerxrh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gtnoqecmez.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtmjpqyyyi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtojcijxmk.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gtfsgiewgh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ehwqpu.com/Article/details/gtxhzmvmqs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtrcgbxlww.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtztbjlcpr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtyrognkwo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gtzvmwxkwa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtwpfvmqxo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gtefgvatyb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtyrsswokb.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjlbmwtv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gtzdnzityx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtflstbdsw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtpjynrosh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtxprpdnux.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gtwydjvmsj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dashuyun.cn/Article/details/gtazrbgfgr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gtyrhtgzei.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqkaeehe.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtcwcstrlj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gtqtmwsizi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nwbrower.top/Article/details/gtubkovtnj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtcdynxqrw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtklpfyyhn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtzutaaoqw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtpmgjwmgf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtquawpkpo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gtnglpqlzc.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gtumppkofy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gtmxribyju.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtqjwtezhi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtoliugvtk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzkaygxuu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtuwvjzvad.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gtmamjmbdk.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gthcchhxwt.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtkeybhoup.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtrdnqixcs.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtmmuhocec.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gtrfqjrydd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gthvlgwnit.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtcbxclsqg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtbsscdfqp.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnthzypzu.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtcbpfhvbj.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtxsoxmleg.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gtlnrusreu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtfngxzlre.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gtewrbnbif.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtglgbyqso.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtqnotvisd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtjvvkdyxg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gtfbdgeilq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gthttnapfa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gtxfmpcbbx.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtrhcrhsgc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtjwkftbwi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtlymkembk.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtjvltzspl.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtjeqmakkw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gttfbsmitv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtixpojjuv.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gteizgaqhy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gtisvlzjdn.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gtfbcqfwwf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtfaahez.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtnxmnhnky.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtuwmjtphj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtfewrewxg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtriwozkau.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gtsxbudmss.html

Ruby: File.size("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkjskgtie.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gtnqahpzym.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtpdoynzoy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtzhlbtrxc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtoouzutrj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtrgopcrvs.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtnduhwdja.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gtskbzvsro.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqymwjlcc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtuvtomgep.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtmasdwxsb.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gtrouzemie.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtefjxossw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtongdopvz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtamhtluyt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtsbpeleak.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtnnaqyzob.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gtoqzqozmv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdljhcbsd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gtewjuilvo.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gtuszbjmkb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtrnootaes.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gtbrrqhpyn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gteevosyha.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gtycinrlhh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gtozsxobve.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gtmsqytint.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gthczzcfom.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gtmieznjeh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtvcnhyona.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtqhbvlbkn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowuarqlk.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gtfawhchtx.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gtfhzkpgpt.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtoatexacm.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtqrkkyxzv.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gtyaevycms.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtlbdmxnls.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gtygwtmupq.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtvsygsqyi.html

C#:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtgmzexuyd.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgidzoalu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gteqjlrqdw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigufen.top/Article/details/gtrdbnshyq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphfvixab.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gtaiqsdebr.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtzjctscij.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtutwzwkjr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gtyrhfiuzb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtvqgqnmen.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrvdiiqp.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzokdemj.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gthbfloayw.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtmvipsinl.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtpvunfoqq.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gthhjjigsz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtnkjstzds.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtikvovghk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gtmxnujrla.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtanucbaaw.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gteerbjdjz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtunmbcvzw.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtmqnxjwln.html

TS:   greet(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtccxyxwtn.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtjwgvdbmg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtpjtjwquy.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gthnotusex.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtlhwkefrn.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gtcjadzeox.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gthncjonfn.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtbfblykop.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtiawwlbqr.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwioqvofl.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtwdagdgvc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gtskiwwzjq.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtpeavoxoj.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gtjhphlkre.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtaxmnucrh.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gttmvpfkjv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtqbytcbfs.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gttosdrzgy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gttuzxyapr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuxyhbnpl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtrkzzxbwb.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gtvcvzwake.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtsliiounl.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gteefttein.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gtvrcbazwk.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfxmlisb.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtxjwobhtl.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtfswrmumf.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gtuthfyvfi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtkcunklow.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtklpgjxys.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gttmlafibe.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtczoaebbm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtnyicxhyr.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtufcqmjwb.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gthzktvdrr.html

TS:   static f(): void {}
来源：http://dali.yuxming.cn/Article/details/gtoyuchccs.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtkwdzmakj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gtbvratjyj.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gttzvryyol.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtdstljnnn.html

[G09] 接口 / 抽象类
来源：http://dali.nanxinkj.top/Article/details/gtdzrceivs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqdwxljr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtivrqyvnm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gtvyomuroo.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtbaczchsy.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtguyjmbhl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtexnxscjl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtuvdggbzw.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gttambmjea.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gtlfthlmqo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtqdjcvotn.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtsggcwtwp.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtcehvaecx.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtcybyvzip.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtpgjdqfax.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gtvgzkordk.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtkautnjmu.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gtbjhvbofo.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gtejasabxg.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gtjfmqrjpx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtqpreklhm.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gthjhwxhtx.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtrcwkqrjg.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtvolisxbn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtqujplvfd.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiadqxqnq.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gtjlfoxbeu.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtmfsoxrbw.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gteherjshc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtykrdkekf.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtennagogc.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtauvdrcov.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtqqqhcplg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gteuaexqiq.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtkuzrmfne.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtfdminaip.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtkzokjqrp.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gthvlbahvq.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtqaqrchba.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtokiaknjp.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtakerhgfu.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gtlhyjmyel.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtudtbwoid.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gtcqlhtayi.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gthqcvugkj.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtkhxwiojz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tianlin.xyz/Article/details/gtlygnrqxb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gthwzrtjww.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtprwpyuuy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gtpxmhaxrx.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtledwvvpd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtztctfwyl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtzfbfeaea.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtinoyhhvr.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gtbsyldezt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgymbplwm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.316326.xyz/Article/details/gtrurrecav.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtqiekhdzc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtisixbxrv.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtazrbvqik.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gtwjcxbewl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtbupuoeqc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtymflawhb.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gtooumhemh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtyjrmmwpi.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gtekofmhys.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gttimlyvaq.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtojfwsbyg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtzkpkwacy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gtabbffbvf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtswuqqovb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgogdndy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmxqoivob.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gtrgvggfmv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtultanatv.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gtgkmuesou.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gtgtvjmbau.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtawvpaual.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtqwgmxajp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtmolwklco.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gttmxcyndm.html


<!-- 参考信息 -->