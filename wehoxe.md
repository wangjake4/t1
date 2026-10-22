代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2jbvikett.html

[E07] 按分隔符拆分
来源：http://dali.redwolf501.top/Article/details/gt2bfctmjbz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljhvepjm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cheryme.top/Article/details/gt2gwajzoqn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dianchejie.cn/Article/details/gt2nwhcnlzu.html

TS:   s.split(",")
来源：http://dali.316326.xyz/Article/details/gt2gfgojtsg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gt2uwjlmgdu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwtyurwi.html

Ruby: s.split(",");  s.split
来源：http://dali.gotoacloud.top/Article/details/gt2cgcygcds.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gt2kljsuqyq.html

[E08] 数组按分隔符合并
来源：http://dali.mhx1999.top/Article/details/gt2afcqafto.html

Py:   ",".join(items)
来源：http://dali.zdqjudy.top/Article/details/gt2qkxvvppc.html

PHP:  implode(",", $items);
来源：http://dali.yongpay.top/Article/details/gt2jpftqrpn.html

JS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2bwkucxhq.html

TS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gt2gvqujlsm.html

Java: String.join(",", items)
来源：http://dali.hnqzz.top/Article/details/gt2knjagpfg.html

Go:   strings.Join(items, ",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgboyqay.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2jlkfnjgu.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tkponpdg.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gt2pbveujzv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ivvv.top/Article/details/gt2fliwrruq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gt2tcufowed.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gt2ygfritjc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gt2rgsamjzo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gt2mvigdvuk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sxryk.cn/Article/details/gt2dtpmyevt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yueranfly.top/Article/details/gt2ypeeegep.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2kmchswcg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gt2iicciiel.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2ohslmgxs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gt2gwkkaqgb.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gt2vtnnxyio.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2ejhhxyks.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnkbgvv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2rvllemou.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gt2tfxdesro.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgpzgqgc.html

[E11] 反转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2zixfkuyw.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2nztcxact.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2howxaeal.html

JS:   [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2fosowrny.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2nkxnkpda.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2vkgjdcet.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2yrlsnbju.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2ptxkmvwq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2sacgztyb.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2aumdjdhd.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjihezld.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvhdrsff.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbiawcjj.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gt2mkisbcwz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gt2pbuqozjd.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gt2tkbiudlx.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2hpwkablt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.haohaochexian.top/Article/details/gt2cagtckll.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gt2avldtoir.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gt2ixfsqxlm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gt2qnxhqgqa.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thmamvay.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2dozooonr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ammetnll.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gt2rvtrwhkm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sxryk.cn/Article/details/gt2ezdxekaz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gt2gyzwbxcm.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pleinkqi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gt2jujpongq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zycfv.cn/Article/details/gt2ngabvnba.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqwixitp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gt2gtzfnmtz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbprgzcl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gt2zszbqgpy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gt2bpkaywru.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bijqbudu.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpfoiebt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdwvnyvf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gt2fndfytli.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gt2srtkkoiq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gt2zamwcieo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gt2voorxnjw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qyrybtmj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gt2dzaoboye.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.andypj.xyz/Article/details/gt2jqdzxxaa.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnurmfci.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gt2cckeanqp.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gt2jenhnavb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2qfmzodwj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzwewmdu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gt2jagtqlck.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gt2kivscrug.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gt2uauyrbpk.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gt2ystubbpb.html

[E17] 首字母大写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lztffyxn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gt2gmaerfeh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gt2cvrzhhhv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2todudxel.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2dufbwkpk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gt2upolwzom.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gt2yypwwvxh.html

Ruby: s.capitalize
来源：http://dali.ybcxt.top/Article/details/gt2zkmyammb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dovhcumk.html

[E18] 模板占位符替换
来源：http://dali.bjfxy.top/Article/details/gt2lbcbyhjy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gt2ulghurev.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gt2rxircexk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gt2tczyucqs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2foquxhlh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2uecbrbbv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2alplcjhp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqfpeohk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irpwasxd.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qotqinxx.html

Py:   s.splitlines()
来源：http://dali.tianlin.xyz/Article/details/gt2obrnsyce.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gt2kjjutlmj.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gt2kwsampip.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gt2xmjpnuss.html

Java: s.lines().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvdybgak.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gt2uspzkdol.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gt2jqmxokfn.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gt2iotmogyp.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gt2kfgkfgiq.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gt2idwdlcpc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gt2zvroqqxy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gt2eidrfzun.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ursznrbr.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gt2mwebsyjv.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gt2cyplshwf.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgcfwbdf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gt2gomjgrtw.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gt2inryjzlv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gt2nslgcvze.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2qqodmzrk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2hpzbqvyb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gt2rhkbgead.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2iyfakpmd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2xxoonpii.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2gxuizhrg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2bxwhpdkx.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gt2idogcfda.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gt2wxasdnye.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2owffuksa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gt2lpdpunua.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2wfimeguq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2tfyqwgbs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gt2gdtuxagy.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2ebowquxs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gt2flojbmcl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2lzwtujcf.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gt2rttreviy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jdkuvmts.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gt2cwlyrvbc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gt2vorhvyyb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2dspqnwrk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gt2bdihrgam.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2xekvugrx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlzwcxus.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gt2gevufggb.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2mafmeidc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2wwrbiuly.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gt2fatmiyqu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gt2zdjaewqr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gt2wpbcbfyg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2hasgpwzy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gt2tkttiejb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2xdmsqcpr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pridpccy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gt2ikdwyylq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gt2ftapxksx.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gt2yuxponhx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gt2qmagdvyu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlfhywpj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2jssnueps.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2maquvszp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2pqofcrjs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gt2jzcuzchl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gt2dqrpdybt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2juryohez.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gt2mzsnynxq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2hzllwhkd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gt2egolmcwv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2ryvehoyx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2ceuugpbw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gt2znckbccl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gt2veryvalg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gt2csrctmpg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pppiwnql.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2sdikdtmj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2brqkupfj.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2thpqsmoz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2ksdvibzp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2xhpmbpnq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2uknqivhh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gt2npqlqyyg.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2wsxezxpn.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2oxknytdz.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gt2nmzdzjmb.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2brwqwemw.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2gnnqqugn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2cwvnqxct.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2nfebtdbf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2shkezddh.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxgczyoc.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2hfvllldq.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2vgcykjgn.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gt2gxsashdm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gt2gjzalach.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygsfotkr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2njyyeyen.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2ecfoqynf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gt2zhwgnpfc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gt2lkvytloi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gt2pjkoptmv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gt2jhniyzkc.html

[F08] 遍历目录
来源：http://dali.chenzaomai.com/Article/details/gt2gwndkehi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gt2zjxzhnqd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ydxgdiob.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ermwxcod.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2jsmrmupk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gt2vcyavzxz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gt2lzzfltoa.html

Ruby: Dir.children("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2uconbxxs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gt2lshkdjwc.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gt2nzqfpbmj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2kpqadllg.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2jbdoegim.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2nglpclam.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gt2lxrgchcx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2dqdtblzn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gt2djpeggrt.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2bmelvjku.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gt2darxhbpk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gt2uwckhmfa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2xgymeyng.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2baqchppv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2uedmdlow.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csakbuoq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gt2ztprpdll.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpaawcpi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2yvdnlmhq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2xzapjkzq.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gt2oedswkub.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2lkaawpcm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2bckzgqpk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2hnbcxkpu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2yfvnjvuu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2zvjkhbva.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gt2xujdfhsm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2keslaqdf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gt2flswzxpx.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gt2hdgohsoy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypeksemb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gt2fpcxjkcz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gt2nafmyiru.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gt2fclzlvrp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gt2fvwybbci.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gt2ygjrznsl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oyqcxqxe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgacgbgg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2vcostkle.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gt2fglneldo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2lossbttk.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aynehetg.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gt2yyifjcxv.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2vlmbtmbo.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2gzksanex.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gt2qbnrxcpc.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gt2qipcggbh.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gt2blrafvas.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gt2abouavnp.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2pmsopfyy.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gt2egtfucky.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gt2sxhqnjsh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gt2gzukmbuw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ccafxsfv.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gt2akjxteze.html

Java: User(String name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2zmcwqddx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gt2pddxhxgy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2dusugugi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gt2guxgptus.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gt2xpzwkktz.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gt2obuduehi.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2owovzcdx.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2mxfuovpd.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gt2spoyvdig.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gt2vuyclrnq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2iddlrwcl.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2ozazvpce.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnqzz.top/Article/details/gt2cvedrakz.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gt2ukzstnfr.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gt2cdumtpbj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gt2qkomtggu.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2eorfsqzf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2qrbieppe.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2pxfmryjn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2jbibpfzy.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gt2sflmzvzs.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gt2zaplpgzx.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gt2rimspoyy.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gt2wnolxmpq.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2dpmdihsq.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2zefsexvc.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2bqyznxbg.html


<!-- 参考信息 -->