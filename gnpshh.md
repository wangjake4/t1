代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gt2cclltluj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gt2dnopydhp.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gt2nnjrmchf.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gt2sgbclaro.html

PHP:  implode(",", $items);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuspxblm.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2nchstxzi.html

TS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gt2wxcxcjcf.html

Java: String.join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gt2wnhnqbfg.html

Go:   strings.Join(items, ",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgeqidxz.html

Ruby: items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2cbqgduyb.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gt2uicghpnj.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gt2jfwjcnkz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gt2vulervyy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gt2fovspxau.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gt2pinitqan.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2vcwztzdf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gt2fihvwond.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gt2wydoztqm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2izfybonf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gt2efgflfno.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gt2pibnxtkw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2iuxfyjot.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gt2dejimrov.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2yfasxotk.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wccsmzja.html

Java: String.format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuwralwu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2uzxqgrhs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbukgper.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gt2ximmgecr.html

[E11] 反转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2tlbsjpaq.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gt2cesvlgvu.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gt2wsstsqho.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2jdmtdyrv.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2piagsakd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuanzx.com/Article/details/gt2jetmactq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2gadrfwjw.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnnoipyo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gt2xersonyu.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2kavwplyq.html

Py:   s.count("a")
来源：http://dali.fengsongda.top/Article/details/gt2yuimqiyr.html

PHP:  substr_count($s, "a");
来源：http://dali.316326.xyz/Article/details/gt2hrtoygsm.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gt2urlwpfwb.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2tzkavuqv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gt2rucfksic.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2tdnzyxpf.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2vulghsnt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rphtxubg.html

[E13] 逐字符遍历
来源：http://dali.haohaochexian.top/Article/details/gt2eqmkgyek.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gt2uahogfwl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xinyue.icu/Article/details/gt2nonqqerx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2mahhqoln.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2imqxgcxl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2lueqsdvm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2fooysjdb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkmlyjvc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2qojzhkko.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gt2hkvlvnmi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okcpbsum.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gt2nyiqmhup.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gt2uhwserxu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jbrzmihp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.meibo888.top/Article/details/gt2zkyfzpft.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gt2kblgepmt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2ywramsyq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gt2zctsjotg.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gt2tasbutai.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gt2kfgkjbfa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eriayfdd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gt2sjwjvpro.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gt2idbuunrd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gt2xtoumkjb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gt2npkabugg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gt2tlshkaej.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pycfn.com/Article/details/gt2zzekdiyg.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gt2msnzalnw.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gt2ldhdxlyg.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gt2djmxhinb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntpeyuoi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2djuupftc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gt2bulnijze.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpxbgihu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2mihkcglc.html

C#:   1234567.ToString("N0")
来源：http://dali.tian-w.cn/Article/details/gt2inqmsvwg.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gt2kvwanwqh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gt2ldljrgyf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gt2sxwiritk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gt2bnkfkjpg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gt2irbndnng.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yongpay.top/Article/details/gt2deqbslil.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gt2hrviyxtk.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gt2yoveiplg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gt2wxarxiau.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gt2mgumgsdz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2rogocqif.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gt2cfaruxvd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2lemncxvc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2ojqjtjze.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2ktqgyjpw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvhizzjd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gt2tcriidoh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gt2nyuyztkb.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gt2pylbrjqm.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gt2ypiijsat.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2dorjqqut.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwawutqx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yuonsnrv.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2jluhdihy.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2jndacicz.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gt2mfrgclqn.html

C#:   s.Split('\n')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kaektxjn.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gt2ouusxonx.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uyolvixh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjnpshiu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gt2kogbbdgd.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gt2prxmleit.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gt2beszgmju.html

Go:   if s == "" {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2meqlunje.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gt2oqzstfbk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gt2eriyshxv.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gt2ojwxwcjj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gt2cmiqulbd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzngjxcu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcjhokha.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2zmimoxkl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2mthnkwff.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xinyue.icu/Article/details/gt2gduwptcb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2jyilzhkn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2osgxovpb.html

[E22] 字节长度与字符长度
来源：http://dali.hammf.cn/Article/details/gt2qcpjrltc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dashuyun.cn/Article/details/gt2vmsphbdp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdppbvfa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2jumeauts.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2jwkgimyh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2irpafesx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gt2zboqvmjc.html

Ruby: s.bytesize;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2ztwkiitv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2ypsszwmk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2jdeydsvv.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gt2kqedplkc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2fchzuwtd.html

[F01] 读取整个文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxamnwty.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gt2wjwcbvtc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdpfxvzr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxinkj.top/Article/details/gt2dpnsbpod.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2pctqequq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2iedfwdza.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.mhx1999.top/Article/details/gt2rxauplsy.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2qxfqfuoq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2mtfglcrl.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gt2qoxhzgpl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gt2epsszeem.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gt2nyargpqm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gt2ozyoonlv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izlbabtj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gt2ikiriiim.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gt2hgsjyvjp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gt2kyrfwqvd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gt2jncmegid.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mujdgfhk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imnqkmpe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2vblfxtew.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhxfaber.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2harfxssw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hammf.cn/Article/details/gt2prhvjknu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dashuyun.cn/Article/details/gt2xhwnppav.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdfzomnh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqpttpop.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gt2fkzzghhh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gt2lahzpiiv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gt2nnbydobj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2rkzzspme.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2uscicopc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gt2dctjtizu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2pyzxfjha.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iivmuixx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gt2nrbbzimw.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gt2tkjghwqu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gt2sytergum.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2gbrzbhtq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2dsysfgqb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2jakiyzsa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2udmnjrcm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gt2qajdpqsj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2mbezanfp.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivnizytv.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gt2ucqnyzfy.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2fybrjwsm.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtmslig.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ebouvmrw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2copvgrnx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2fnvwjvie.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2bcpdbqbg.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbqfspqf.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2pwamhrvy.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gt2henieugw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2cjssibrt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gt2hobcmjmw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gt2ubkxeqxy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gt2zqcyhjym.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gt2lylmqorq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gt2bqkuqoie.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gt2vjqqxijn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gt2skqzkbps.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gt2dmfaydqt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gt2zxjwpqyp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gt2ehnsgcqs.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpvpauyd.html

TS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gt2vhgkyjpi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2ytyazwzi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2ffqpeqhv.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gt2ojxpxinw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfheqkce.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebndrvou.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akafhels.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2wxozmzzk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2sbikginn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2ugycmcvy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2grexhzhb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gt2uvskmjot.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2kqbzyhjj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gt2qqonsdtw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gt2bihiudfx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmjkgvno.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2ayqidbtu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2sslvegrq.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2tzypttlu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffosjxqz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2zgfliltb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2fyfdonhu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2dpxvehwy.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gt2bghamamg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2qbkukgxm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2hzcwtvkv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewnmudzj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eiuiphpo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2ndorwnzs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2oyhipbcq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2rwhjwjvk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gt2aoucpenw.html

[F12] CSV 读写
来源：http://dali.dashuyun.cn/Article/details/gt2jbnaetei.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2mmljorpk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxltnajq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gt2qvguefph.html

TS:   // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjhtvljk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gt2vmalmtkr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gt2wvvhivjy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gt2iuetlrtm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gt2ijsleney.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2byscrsfp.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2esojugbw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2fkiglvxs.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gt2yfscvqgr.html

Py:   class User: pass
来源：http://dali.daxiang520.top/Article/details/gt2moojjtaf.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybrmozvh.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2evxttwfw.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gt2ncoobrdf.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2ppougswx.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gt2tkzawudo.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gt2mxeatcca.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gt2kcbvxgsc.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2sozjczbg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gt2znzmrzjd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.svipenyu.cn/Article/details/gt2uaecaiib.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihrsetge.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gt2gmidikbi.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nbuqoqrx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gt2lmqumpho.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gt2gjsipiaa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2lggyjpwn.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbsfmfdl.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gt2opsztyln.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2ngjptfkz.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2qaudnhry.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2zslzjxrx.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gt2vakekcre.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gt2snnzylsg.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2ysjydgsv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2rtloxovf.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yggfuiyg.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2ajrfxehm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2ccakwnuy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnlmztq.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2prbgdajd.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2grjttmhq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gt2ucpjsyre.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmtqdwsa.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gt2rgqekkpf.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2ukduoaqh.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gt2eyvdewck.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2xpvdmuyt.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2nnxqojfn.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2mbnxkwjx.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2vfvnqdsz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gt2qmydhkja.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gt2kiddaguy.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gt2cxuvfxyz.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2zezefdee.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gt2cgnyiyck.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2whccvwrd.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2mmzkkpog.html


<!-- 参考信息 -->