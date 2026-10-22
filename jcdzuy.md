代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2rdxxlqkv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdupcwrv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gt2rywofmbn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2guflaldx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gt2wnlxqhyi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fzhhl.top/Article/details/gt2yqtrycyh.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2znyswwtp.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gt2iobxoqnn.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gt2wlfeqlcg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgcapkrc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gt2qxmkdslw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gt2evcwyvlg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gt2nrkoujxe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gt2tggwaknh.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tpaqoynm.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gt2rvcheavc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gt2wfrwcslk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jsnnomkh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2ytvdpdsh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gt2fzuaivov.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxinkj.top/Article/details/gt2japfkixs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gt2zyxicgjf.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gt2cyrykhnl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gt2afbioqoa.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gt2jtydefnn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.vqdsnc.cn/Article/details/gt2npnxcbwc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gt2bvwzjhgn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2vejsxlbf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2xcewjtiy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2hqjilmqh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2eztifwuj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gt2qtcfmhcm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.haohaochexian.top/Article/details/gt2xqnnetyk.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gt2pbwoglyw.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gt2mgfrtugj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gt2piqkaaxx.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2vdvcgncj.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gt2gkmycyii.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gt2ybylbwjg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkmkrcwu.html

Ruby: s.lines
来源：http://dali.jinghuilouyu.cn/Article/details/gt2meulyfyv.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gt2lqyisjjc.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkmngvqr.html

Py:   if not s:
来源：http://dali.yj202588.top/Article/details/gt2clwojqhx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gt2hqnyusyk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.redwolf501.top/Article/details/gt2hbceweoh.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gt2bkqstzvd.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gt2wlitabkt.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gt2qpgwltmw.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gt2vifuxzeo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2zvsajzpq.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gt2ynueemzl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gt2tfubasgj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2mvtiiagp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2gibjufbf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2osnoudfh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2rbyfuvbu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hazjiczd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwfqdton.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2wfenuhia.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gt2ccbaoshv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2mefhwrbo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2svurkxzo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uakhivnp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gt2vdtdjryl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2ffszmpwb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gt2fxdsdkfb.html

Ruby: s.bytesize;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2ezysikie.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gt2aslumqqu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2voxcroma.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gt2zcdwyhal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dherrhnm.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gt2nsmucjji.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gt2qtachxru.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2ujrgyawn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xinyue.icu/Article/details/gt2iceohzij.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2wenxyzse.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2hqsnfzud.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gt2dyqilsdn.html

Ruby: File.read("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwfqnhba.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gt2dmvlamsf.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gt2fzeaewws.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gt2nedrkdtq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2czdqbldu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2tpbvvcxd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gt2jbtpkdwb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gt2orxputmy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gzhubu.top/Article/details/gt2ikwtnlsw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gt2csdzxwnq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gt2joalxhhu.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gt2byvwafxg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gt2uxybrcny.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jiqqyjot.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpmtdhpe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikermeds.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.guannengcc.top/Article/details/gt2qkkdatvi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gt2bkqjctck.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2ilmzzksw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2bpywdoik.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gt2doqqldir.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gt2dxlrbdfm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258888.top/Article/details/gt2yfzljfiv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2dvsdimhu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2vtcgckvg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gt2tikwuard.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gt2xmflwkpy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gt2kalzyemq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gt2atoelwfb.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gt2pqwcqjlq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nwbrower.top/Article/details/gt2urnsidwh.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2kyxwumco.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2plvqcbdx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2lsginiuc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2kiyfgamk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gt2vgxvfgxh.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2doxhkrqx.html

C#:   File.Exists("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2fcegxjer.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fklwkvay.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2zmpsgcgb.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2efmgtwik.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2jbsozoik.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2yxgpdwey.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2jyfkayen.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxbpoxnk.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2zhzwedqy.html

C#:   File.Delete("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szldgsdk.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gt2bfklpkoe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gt2ybjyzkho.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gt2amfmyhsw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2cftgztws.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2cmjtahww.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gt2srtzsvnc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gt2ylfpzjyy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfnaawmu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gt2rgioefwf.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gt2izgbzfxw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gt2vryvkpgc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gt2bqycnkdh.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2bwqsxxsv.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2lppgcyhh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2lendmfpm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gt2fkydlyxy.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gt2dlwczjsm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfcoocvh.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gt2jhftwecd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2nqqhpujb.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2tbeonbyr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2cazfswvm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gt2ykofaotu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2fvoakstq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gt2aoganhsu.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2yyqbunwm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgtezpmz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdmpdsuo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2cflulowr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2okelawqw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2xpbewznx.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2weenkawa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gt2aurwdzlz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2rvzkrgen.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2ymilrhbx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2lfwxqusk.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gt2wyfkcptv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2uvadwwqg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gt2vbsohoaz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ysdzxswj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2desbrdvy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2eykqpfat.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqmihlch.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2lshncrkr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gt2pblgquoo.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2jbsygmta.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gt2qfbrrvtv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gt2brlijvpy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gt2hmnjwrwl.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gt2gfuwotpm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hffdljpz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gt2gtpmsfpm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gt2nlcxvzug.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gt2cfoayxcn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2xrawtxbp.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gt2uwqgcwpf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wnkmiyik.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gt2yjysitgl.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gt2wcglokgf.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gt2kapucchc.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gt2qgsowoxa.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gt2apqaupjg.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gt2attlvtnj.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gt2ioeswjuw.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gt2xuhuwmqr.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtvxeeki.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gt2qvgzskvb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gt2yniqyagn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gt2zapluxlp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2dpcpuuif.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gt2swkeztvr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2lnzlfbxp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gt2ugeyscwg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gt2vdyuwqtq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wiwdpgls.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2exohbnza.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2oiwaypnx.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gt2wiaeqjal.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2kwpuqfjl.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2srssynlm.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gt2pgearlmy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gt2pfiiflfr.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2eshzjsmk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gt2yvvajwby.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gt2urdsolgs.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2mvmflzvz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2xeogsyns.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2dpwdhzxg.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2qmvjwvim.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2ppkucwke.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2kdzjbyfn.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gt2vxthpdbc.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmkkoayn.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gt2hqptrsgd.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dyvqheeh.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2wileiliq.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmiclosh.html

TS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2ehsubqae.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2ohdmwais.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gt2zjuaqqgb.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idzsfpdk.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ppmwyoxf.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwjtliwc.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gt2zqydffio.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2amfpzjzm.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jxzyzuuj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2vqwdefba.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2nseaqrgs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhoulong.xyz/Article/details/gt2rrutkfvv.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gt2bvnwmymk.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gt2tellzkcl.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gt2rtbmwnka.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gt2kebhjmgn.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2uuhyyxbz.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2uilgnhrc.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2qyshytjn.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2iaajdffb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gt2mwuupums.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gt2nmcpkmyr.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gt2qvbqsmic.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gt2iekjpdkd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gt2wyvegvxm.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gt2ldyojczb.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2cvofbcpx.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gt2dcfjfjrd.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gt2dtgjaowq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2wfnhecuz.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gt2pavvkwfu.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qczyncnp.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbeznfea.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gt2vyjbyxui.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gt2mipykmmj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gt2gvuspthd.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gt2ygzrtizw.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gt2whzncesn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gt2adwynuwg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shzaibfc.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gt2uyncrueg.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gt2vdknvutm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbxdvsbu.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2rlabtnht.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gt2saqbeplc.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2aaxafizi.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gt2sckmytfb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbnlnfmg.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2jjuhprcc.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gt2vctrhrpr.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gt2yoeunnlm.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gt2tmibctqw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2nkzucpmw.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2bsiibkqx.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qwgvrvho.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2wfeukksk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2vndpkzep.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gt2ymuqjwef.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gt2iirwhigv.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2tcgsktms.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2ecmhisgh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2jofmojsh.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2qztfyqzj.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2tplslmwc.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2tbuxcicm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2bfsukfxu.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gt2ualugxeh.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gt2bopksgwx.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gt2ooilxqoz.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gt2hmokhdxz.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifuuckpy.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2kszyyfur.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2bihbqcra.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2yoxvicxx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgfzy.top/Article/details/gt2rmfvuoad.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gt2vgwgyzir.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gt2gpmwwybx.html


<!-- 参考信息 -->