代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdmhlgtk.html

[E07] 按分隔符拆分
来源：http://dali.jiagoushi.top/Article/details/gt2agdfskvj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gt2dbdnisld.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2qmjpphfl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sxryk.cn/Article/details/gt2xbsulvll.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gt2adntsruq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gt2gtnmqlbi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jianghu66.top/Article/details/gt2dhdpgmmw.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gt2kbxznqyl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jlsjyb.cn/Article/details/gt2kgnkgflf.html

[E08] 数组按分隔符合并
来源：http://dali.chenzaomai.com/Article/details/gt2rfrchewi.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gt2dyfwfqoc.html

PHP:  implode(",", $items);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ssnnumjz.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2qwdrlguo.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2alxyjyrl.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gt2mouyyyfy.html

Go:   strings.Join(items, ",")
来源：http://dali.tanke756.top/Article/details/gt2vrkrzcmq.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2jxqmznum.html

C#:   string.Join(",", items)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcvienh.html

[E09] 去除所有空白字符
来源：http://dali.gotoacloud.top/Article/details/gt2zuegnomo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gt2ncgpmmvk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2swvouzvo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2ibirxpyb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ympqhomp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvpjmrhz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.haohaochexian.top/Article/details/gt2vejcagft.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2rpidqywl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2cvrlbhjb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gt2qlizxtyf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ufuxlzyy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gt2dxdpmxoe.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvlfqbgc.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2btelorwd.html

Java: String.format("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gt2wgcbnypn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2ilgqwitt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2nlwnrfyz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gt2eaayhtrt.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkrfsphb.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rnrcixva.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gt2ildfgwhh.html

JS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gifaelyb.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2bxvjzhbt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gt2umeuupsf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gt2tlwpuyre.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2jhvkyhwe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gt2xcwjycfg.html

[E12] 统计某字符出现次数
来源：http://dali.aibaodan.cn/Article/details/gt2ebawekoy.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2drbuvber.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gt2dhmzfwep.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2gxmcofcg.html

TS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gt2ltmuocvi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvpbjvz.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gt2xprlhzrh.html

Ruby: s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2nthycimj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.mhx1999.top/Article/details/gt2fxndrbmi.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gt2usugdzmy.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gt2khzllcye.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbmxkeye.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2fxwrrgsg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2gpixzmym.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2fmiqzgxy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gt2ytjtmofp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gt2aracwdaq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2arqlegsu.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipqfksxk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gt2iohkofxx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gt2nsqnxtky.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gt2pybervbb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gt2scudkinf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2myforagz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxgpfggy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gt2mrtnruyd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2tfvsfymx.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gt2uhtxxsxa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gt2kubcjbtv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2lmtzjwkl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gt2gpmprxvt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gt2uqhznbjc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gt2pldsiogj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2rbtpnbab.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gt2qgbfyigg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xinyue.icu/Article/details/gt2yneqvaqq.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzsjlsdj.html

Py:   f"{1234567:,}"
来源：http://dali.jianghu66.top/Article/details/gt2vidtichf.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gt2whfbfraf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gt2xwjomphr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gt2dygmtufw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xinyue.icu/Article/details/gt2wvxssgod.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxuanxn.top/Article/details/gt2plpkptoj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gt2esvxgqnf.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gt2qbigoycr.html

[E17] 首字母大写
来源：http://dali.nanxuanxn.top/Article/details/gt2puplxnqq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvdqgvwm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gt2eakyvoic.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gt2hmsgugnf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2cbbkqhmt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2htmztrbl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhoulong.xyz/Article/details/gt2bajyxyew.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gt2nhdooopf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gt2cauapfig.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gt2uyuhpmle.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gt2zcxsyyxw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gt2gnxnrqdc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2ereummtr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2omhdvouy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2vsoefqsj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2igtuefzf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gt2caynfjnw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gt2bdetjqrr.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gt2ulrknvjp.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gt2mdtfsuhq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pycfn.com/Article/details/gt2yeieqvvl.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gt2wxucjsfa.html

TS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gt2iyloysye.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2fyxzvxse.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gt2owqxynln.html

Ruby: s.lines
来源：http://dali.gotoacloud.top/Article/details/gt2pjkwnagn.html

C#:   s.Split('\n')
来源：http://dali.hfpthk.cn/Article/details/gt2hifwwmwc.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynsnsowv.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gt2vvcyuvci.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gt2tuxgixbz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2irrbgrwx.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gt2fjmylvwx.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2wyyiwmtt.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gt2zgxfyulq.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gt2xbaoevpf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gt2feodbyrl.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gt2djzunzkd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gt2tsljzfay.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2qhzhxztl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2azlfopax.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxleizcs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2uutyetpg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gt2zpukycal.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2vldwewkp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2uncyfxsu.html

[E22] 字节长度与字符长度
来源：http://dali.sxryk.cn/Article/details/gt2eaaksxra.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfwsntwl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2hpeacgyu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2gefnbrxx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2eiysxqof.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2jgcuekbs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gt2snwimtie.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gt2fatqoydy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gt2tvsiplek.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2yksucjag.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gt2napbpvpk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2bcbbbwgc.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gt2puzexvba.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gt2nodylpjd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2oftokdxc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gt2mboetths.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2qzrrxxil.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2qvmarhpu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gt2ffmluxqw.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2niaazfgk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2qgcribjp.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnkohkh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.redwolf501.top/Article/details/gt2ogropegr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gt2oshlolsz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2xhqlobao.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zxhnxgzh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gt2owdfenel.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gt2zfqgpzge.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gt2ruuigpft.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhftajdg.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gt2rpvgbhne.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gt2fkubedvm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2anivntxc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2fmbyxizs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2flnmnbyn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gt2urrlvwhi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gt2pewwzsli.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gt2tqjwhude.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oofyonwu.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gt2anhgpwub.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2wbojvubf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gt2zctsjxfa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2ysoutxni.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2zppgfjcr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gt2kbxngoea.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnibeimn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gt2ligcxgww.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gt2lkwrolsn.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2yqkadhho.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gt2xnjwuviu.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2upaljtyf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tyoukwft.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpsuvuey.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2ylvunytc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gt2llhpixuk.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2dydrfvnb.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2pgimpzai.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gt2xpewhqpj.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2eselxiad.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2xnhdusie.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2hslqrbav.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2hsfqgnzg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2ehufhnlv.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2jcmcekxv.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpsleuqe.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfmvwauj.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gt2hxjagqxw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gt2hkleevhc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gt2dwznwqcj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2ubwnvanx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gt2beeyfwdh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gt2sygqxzds.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gt2hnmbtwxg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gt2nsdesfts.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gt2dmelkmgg.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gt2zkebgcgn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ezreemrl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gt2yeiqruuh.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2qjmbcdqx.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2hgfenuhw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2tkyhqggm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2trqvpvnz.html

Ruby: Dir.children("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2ezyhbhug.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gt2zaqjmsqz.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gt2gytryzgn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrinbodk.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2crrckkom.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2wjdyxtuh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2kdwqsrez.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2yfskqjqz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gt2gjovyjzh.html

Ruby: File.size("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2kanvmfxz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2fqldttmu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gt2lmeujecu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vehmznny.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2lvhyvwyo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2ihckynum.html

TS:   path.extname("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2fpjjzzla.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nkrabzre.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2kycdnvrs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2uhkpesqc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2fxeyuwzw.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gt2bozcwdjy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2pkvmgtlu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2xnjgderw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2taezjrfw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2asofjpzv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2crynutet.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gt2dudgkvcq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2lhatatqu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.kuanghao11.cn/Article/details/gt2pywfczdz.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gt2omvmbcup.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gt2kvygnezj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gt2qlecyfri.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gt2dcokyxhg.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gt2rdiprjup.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gt2xfqsnjyr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.snrcjt.cn/Article/details/gt2vgpodnva.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gt2lfykjdfh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gt2kxtzsqht.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2csuwilff.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gt2eihhtqdh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2mmtlezxh.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmanbtvi.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gt2uegifgrz.html

PHP:  class User {}
来源：http://dali.hammf.cn/Article/details/gt2cnrywajo.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2zygoijcs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gt2ucuwspof.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2uzaxfgrl.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gt2lcdyrwnb.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gt2hupwqwif.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2cdpipjap.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gt2anpjhmek.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gt2mrvwxofy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2zejugysn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gt2pclemmqe.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gt2kbkhxlbq.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2rbepwhrh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gt2cnscsfln.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2potoafhq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2wqhrcmup.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gt2bbrljhir.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2zepvvoqk.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2nxevrmif.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gt2wwgtbtyz.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2qkeikrld.html

Java: private String name;
来源：http://dali.cdnleiting.top/Article/details/gt2isfumxus.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gt2xzgtwfak.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gt2qqckrcui.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gt2pofvffwj.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gt2grvfjtxg.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gt2aykaucvo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2svqikgcd.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ttcsugoi.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2npsssena.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2eowlmihj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2mqjmtbmu.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2waxhnsow.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykxnrujo.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2liepexqq.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ueegjggu.html

PHP:  class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2ysysipwk.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2plfwkfku.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ruqrnpwb.html


<!-- 参考信息 -->