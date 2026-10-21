代发 wailian999

Ruby: s.reverse
来源：http://dali.xinyue.icu/Article/details/gtzcchdkby.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtyihwitse.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtiajpchjk.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtssbqswfk.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gtsegnlbph.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtbjiodkgi.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzqqnopk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtbhgogcyx.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gtbqjicbkc.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gtfpmadygo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuxming.cn/Article/details/gtwlwzgrov.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gtviazamxc.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gtzwauthht.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenzaomai.com/Article/details/gtightlzma.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtqkiugvkr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtwdtosuuh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdmbmzson.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gtoayepsba.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gtahglfpxs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtcggnkkwz.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtgsmqniyh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtpserkzcf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daria6918.cn/Article/details/gtyakjznmd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gtbtdqiasd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gtwkrthwke.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtbyrerzjc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gtoypvvvxp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gtjtlhsfxq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gttzehqqxv.html

[E15] HTML 转义 / 反转义
来源：http://dali.meibo888.top/Article/details/gtmabycswk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrulgirhn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gtsbdyqvkb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jlsjyb.cn/Article/details/gtpkqhrdhz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gtxldvxzxv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gtycoglxar.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gtdbpueeha.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtaaafuydy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtnmpvjqru.html

[E16] 数字千分位
来源：http://dali.aizwys.cn/Article/details/gtrqiueqkw.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtmwhefuoz.html

PHP:  number_format(1234567);
来源：http://dali.hongshengwenyu.top/Article/details/gthsemrrgg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtsegplyei.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gtknbbzmjg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtdhxendkv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gtfiazrpcz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gtnbyaypki.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gtkjfrvlkk.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gtjhfnziae.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gttxstwtnp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gtzlvnsmpm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtygbpokry.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtahnlrqag.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtbvzylpuh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gtryagbatd.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtliuyzbxb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gtbhzyumpf.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtqtdtajsf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gtxvzptcll.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sysykeji.top/Article/details/gtqpqjtrji.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gttgkfctpf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtncqjgzuf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gttdvylyyu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gthcgvjmyp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtltugicis.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gtcuymdqei.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gtrxqyuupj.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gthicqsfbn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtbguoxnng.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gterhlkrkq.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtzwunlpmf.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gtcrmnkcof.html

Go:   strings.Split(s, "\n")
来源：http://dali.ydzc1.top/Article/details/gtnfgqsgvx.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gtzarvpjku.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gtuctytyyk.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtedsmqfdg.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoamgarb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gthwtndvlu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gtlwvdmgfu.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gtlypewxdd.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtxzbnwkqc.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtudouqhwx.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gtotrjbcsr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtnzgauvpb.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtciodrrog.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtyrrlovfz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtluqctzch.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtrxngmidi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtdqzbngds.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtyujuhcjk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.snrcjt.cn/Article/details/gtgctuluok.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtcecwqydv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtscefawvd.html

[E22] 字节长度与字符长度
来源：http://dali.quarkkingdee.top/Article/details/gtzqdumoof.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtuqwgfqfy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtxlgkqkxq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtvblabvrk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtnyprqeuz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtljnirdns.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gtihqazmwb.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtjozuhxaz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtrvfhqwlf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbruifwfa.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gtezzfwuzc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmghmnxc.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gturyygxru.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gtkncokxie.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtzgglsvlb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtfnbzikmb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gterdzdcfn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtmujnheka.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtwmfvjpyp.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtuipimmme.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtrgyviorw.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gtapqjhuam.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpuviobj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gttometrxn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfazsbixw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbdismpr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtnwdkswql.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtbnypltbz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gtbfedcfjx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtdephntzu.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gtcxooxpcj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtwzvgcari.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtfbddjxco.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtoejryrlq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtheofqkjj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtlbzwrdlk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hywenlv.cn/Article/details/gtprillvzk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gtiveidevz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtdmzltgwq.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gtncgibrdj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtxrdcpamj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gtjejzjgdd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtnsmuoyzo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtlosyieba.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gtmdxbaejf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gthaqjjtss.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gtekccpujr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gtpewhbjph.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gtnvopoasl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtfvhjeemz.html

PHP:  file_exists("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnandihx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtqoqbfmog.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtcmolunbo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtqaqejbnt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gtxckfythp.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gtapsltvia.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtqeyovgyy.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtijlxlanc.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtoxiuoawo.html

PHP:  unlink("a.txt");
来源：http://dali.daria6918.cn/Article/details/gttomrdvgj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjgmwzkj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtvwbqphpr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtzdrwrlqm.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtwyabaowb.html

Ruby: File.delete("a.txt")
来源：http://dali.cashguo.top/Article/details/gtvjskxlum.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezxcsgdw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtiymwblli.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtfnwjojxo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtdardwgxx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtdwrgxxxv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtntgkxsga.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yongpay.top/Article/details/gtasdbpipu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gtmhqgbymk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gtkxseknyz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtikkuehrc.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gtysoewank.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gtgkwnzsoa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtcfziiwts.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtlxiaxkqs.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtdtdiedvs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtzqxjhpia.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtpudcxqly.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gttwuwlpav.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gtjcaixlkh.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtnqnfydjw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjysaujid.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtfdyrboog.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtuutsbymj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtprcmgjar.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtrtypazpq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jianghu66.top/Article/details/gtqzrpurxx.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gtqhkmbpgd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhnieifk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbfxifgg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtnlcpvybl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtaajpkoty.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtgectka.html

TS:   path.extname("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzgiqeiky.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gtcwycixic.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtvimccbke.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gteqlprqjb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtpougcorh.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gthcojfpar.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtrmpumwsh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gtdlphxbaj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtkhsifgcg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtkzkfasuz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gttwhddjro.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gtrijccgaj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdztkgbvp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gtywrzhzec.html

[F12] CSV 读写
来源：http://dali.yonumen.top/Article/details/gtmgdmmzzc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gtvkppoztv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gtlyltmiai.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtwdshphoi.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtktfhjbwc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtwavlzndd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtpemdtxbk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtdyzmzoho.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtzoagyebr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmvkbsnhr.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gtsycgaqmh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmzxuajkv.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gtjtpwvltt.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtqoojpjqk.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gtlxuobpby.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtyerclcfy.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpbdxtgzf.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzzoaepr.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtundylkwv.html

Ruby: class User; end
来源：http://dali.hfpthk.cn/Article/details/gtsfpieorc.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtzgfiokmj.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtqucpdlri.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gttsiztoch.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gtabtycrch.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtjeznayxd.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtzojvylny.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtnpdicpst.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtccrrzqbi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gtvrykkyzx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtybzfjgcw.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtdwexxnsn.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gtreyctyne.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtivshhjkt.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gtudstwavq.html

TS:   name: string = "x";
来源：http://dali.ybcxt.top/Article/details/gtrqbbtoxf.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtwpewneid.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmivgvilr.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gtufxtgxcs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtbrepwkju.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gtybylznll.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtnhijhwwo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gteilmavxc.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtrvmvjgbd.html

TS:   greet(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtimxepfol.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtnfgovkcz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gttcgpmtie.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtocvxupip.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gthlzspcit.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gtblawhioj.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gthholisoz.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtcuaiuitu.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtxxbndcmc.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtnjvljlaf.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtfpbwhwyt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gtlwedisxx.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtugtfmaoc.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtwyzdqskj.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtnjdakymf.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gttridcyer.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivsacsqv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjywqorpn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcatlvfv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtlunntply.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtfsbotesm.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowwwjopf.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gttwannghe.html

[G07] 调用父类方法
来源：http://dali.ehwqpu.com/Article/details/gtwfnorsac.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtgzldcxgo.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gtsxxdtqjp.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtfyhbmmwp.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtftpfatss.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtpkdcblrx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtkfdxlmlw.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzugcyujs.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gtkarmmhzf.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtrclgsjtf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtfsnjtlhl.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gtykvubyyl.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaprhvtlz.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gtyegpefpd.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gtwxzvqdmo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtesbsfnhc.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtfucbrugn.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gtzhroglki.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujraymxd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtavfzeaxt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtlstdctun.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gtcafxqfcq.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gtlzbuibmr.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtyjvkoryk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtcrszzjuk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtthojhijq.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtcebboach.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtthznvsmp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtvfbeginv.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtxjpphpxk.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gtnntmgnjq.html


<!-- 参考信息 -->