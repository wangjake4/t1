代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gtowdkgyme.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrodvtzr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtdlemfsnh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtktpvgzdd.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gtuventtbn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gtqvxkxuaf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gtyqjkibtr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimsxynbc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gtmucvskhr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtxcqaefwq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtmfymqayi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gtrglzndrs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.meibo888.top/Article/details/gtpuwugffn.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gtmrtxqbuy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtnlbskmoh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dashuyun.cn/Article/details/gtetbehzzf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gtpnikwlzd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gthtnyqtjv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhongyouzk.top/Article/details/gtrpekpevc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gtbukskfxs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.9152youxi.cn/Article/details/gtgxpsvisb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgfzy.top/Article/details/gtuqfqdzra.html

[E16] 数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtmgdvgvfw.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gtrzizpxef.html

PHP:  number_format(1234567);
来源：http://dali.redwolf501.top/Article/details/gtipobakue.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtjztssoqf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gthiaefyhy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtxrckfgph.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.0kj1m.cn/Article/details/gtvfewrlqr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gtakexkcjt.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtlsbmtckp.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gtxpxaiigb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtlaqkmmga.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cheryme.top/Article/details/gtcvrqhqgc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtbiiqmmoo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtglxstmie.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gtdjfarflf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gtdnslqltk.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtheypnnaw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gttcrvylld.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtgmubbszx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cucudq.cn/Article/details/gtpoeltloa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gtntklomhr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtikqihqsi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtmuyadxbs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtqqmfkytt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqtxjvsb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gtmtotsbva.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gtixsrucqu.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtoqkfghsd.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdoxbktn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gtwxiashrr.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtbcefmaet.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtqsvawfqo.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gtufxgcpfo.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gttqxtxzhu.html

Ruby: s.lines
来源：http://dali.tian-w.cn/Article/details/gtmomiixdx.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gtqicdfbxw.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangtech.top/Article/details/gtuloehuir.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtptggcbvm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gtcepbjuow.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtstnxvcyz.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtvjwzvjke.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtpydctcxz.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gtaufzwygx.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtpvbjwfph.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gtrmznskzx.html

[E21] 超长截断加省略号
来源：http://dali.sweek.top/Article/details/gtzqtsukty.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hammf.cn/Article/details/gtybmsplwn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtghnfcoor.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtrkuprfww.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtgnjbespq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtuxrpkked.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gtjgsndeyo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtckafrjyx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtzfkrkxzx.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gttvccxtlc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtbbdnvcsb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtdcfhpklr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtwsmckncc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtwoojvvdw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtbftyxrlo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtygxoneeg.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvykcblx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtopwzzotr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthikxzssj.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gtlzgkibag.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpslyffmp.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtuzfvlodk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gtaseccuxt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfiazufxn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtgzloonjh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihkqtboo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtzepqslhz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gtnqfplgao.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmrslrfmg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtxaborctt.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gtwxetvanj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyxcmwas.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gtiijyyvbf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtbqnhkwvs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtdofsopoh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxlrpqsx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtasoyyeph.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtmxxdbsjc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gtsnckwwfw.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtcqtjbtcg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtnyhgagtr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysrmzpoz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtwtbqmyke.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbwnagiz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gtdzlzcbqo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkinpungl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtejyyjffx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtirblbuml.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfsnaocdi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtndfmjdst.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gtugxtvjxt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtgaculsxq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gtkpgcaalv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gtmexiozmx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gtbedxkxfe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gtjtduyzqu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtuwulxtgo.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtewzjvbry.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gtknosvvoy.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtuokqhxdg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gthcjoynfg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtynlvtahm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtfvicfknz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuehmybvx.html

Ruby: File.exist?("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtsyojlcgi.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtdhljylax.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gtxnvhsbpl.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtciefoing.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtadorwsll.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gttvqkokku.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtsojuwmtz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtmdxhytse.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtuvcbguqk.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdzvhwpxw.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gteznuhyha.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gteqagifyj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gttwvhxyah.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenlongwang.top/Article/details/gtkcgvzava.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gthqmznzhv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtxdxwfipd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gtfozvhizd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtzijnjzkw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtyzpelcpj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtjrbxlkfz.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gtpulwlgep.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gtgormclae.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gtkvktetbw.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtjyyqbzhw.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtyjqddhmy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtgaliaalx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gtlschqkbv.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtgihwxigg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtrgfmnnif.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gtlcyyzfir.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gthynmnbnl.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtbkjueiiw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtozmbltwb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtdepkbpyc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtpplqgqsu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gtggzdqiyk.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gtmwdwjxxj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sysykeji.top/Article/details/gtwddhemvi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gtmvmhudwf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkztlfjjn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtnukmjhhy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtnwnvukcw.html

TS:   path.extname("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtzctsvnyk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnhtozco.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtgynrffxd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtchxyoqmv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gteuhgzdhh.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gtjfbbztxe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtgadymeod.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gtrthkselw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbzlmivse.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtxneeqjkt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtprzgrgaq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtfmlmiyca.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtvxvltzpg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtaonfyxja.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gtbgrkvqzb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtueopliwq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtyievgfik.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gtprzetjzw.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gtontwtfql.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtururmqph.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlrmxwjr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gtrfmhjqux.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtoeqkrmtg.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjjlngvs.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtbctpvnxl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqoozmgja.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtfrynsndt.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtwhdlxitw.html

PHP:  class User {}
来源：http://dali.yj20258888.top/Article/details/gthhvhlmoi.html

JS:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtdjhroysz.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtugctqxjk.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gtdufjdvsr.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtiwxlsmaz.html

Ruby: class User; end
来源：http://dali.shzxlz.cn/Article/details/gtlhsbbgrp.html

C#:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtchptqcws.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gtibdpjbfm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gtlbiulray.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtklcvjwpd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtmjpwkzwc.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gtvknfngfp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gturxgoyug.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gtnkbfypin.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjqfqzdy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gtepnllrzm.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtxuquipam.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gthuwhmsmp.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtwkxkkswx.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gtqiqgzgmd.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtydjpftgb.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gtvsxdqabe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gtfdkscosg.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtkjshcyjh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gtcxvvsvji.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtoaanoupt.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtmwlkdief.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtrhkxodji.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdezahkk.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtpadmgvwp.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtpucbamsd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gttpvdsadq.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtjipcqbof.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gteanksswi.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gthtkkjcil.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gtgdrjrytv.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtqhvfrjkf.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gttwqpcabk.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtfesswgcz.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtebotproe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gtcknzdodz.html

Ruby: class Admin < User; end
来源：http://dali.xuanzx.com/Article/details/gtilqyellr.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gtiemmtycp.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtrzenezmj.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gttvtfvohg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsuuwaff.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtoypipsba.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtxbholrqk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtksquopoj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gthkrlahss.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtjcxfcjck.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gtkdafkfei.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtulgkossp.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtkxaeljyz.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtlshmzyvl.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtatlepvad.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtdrcoygxi.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtlfmbfmao.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtkkeffvna.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtvvcuzknu.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtnzcbgbqr.html

[G08] 静态方法与属性
来源：http://dali.dianchejie.cn/Article/details/gtehzgsozs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gtppvbinvo.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gtsjqtjnrr.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtuucmlthk.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gtthywsqxc.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtuckrbsva.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gtvapzynqk.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gtgtjpqhhx.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gthwybufnh.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gtwvmjpxjo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gthwtwspvw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gtgyqlrtzv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gthjtphvxy.html

TS:   interface Shape { area(): number; }
来源：http://dali.fzhhl.top/Article/details/gtbvlxdkuw.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gtkhupgfdy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gtpetnnwqx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gtajcdcfqp.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtwiurrija.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtsxbckfjx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gthecjomze.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtmrdcuthq.html

JS:   #private 字段；其余公开
来源：http://dali.gzhubu.top/Article/details/gtqtzzbekk.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtgugaikvq.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtynbravti.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtydufeamy.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtrlkiihod.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gtzqwadcqb.html

[G11] getter / setter
来源：http://dali.zycfv.cn/Article/details/gtwjaogdtn.html

Py:   @property 与 @x.setter
来源：http://dali.quarkkingdee.top/Article/details/gtnikfjwxm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzuwsfwh.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtwzgtkhqm.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtvgsrmfbg.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtgfutkgtw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtslaixqeh.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtgubqcsqk.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gtaeulvupu.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeeekzem.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtctqsrmrq.html


<!-- 参考信息 -->