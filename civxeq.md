代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwmeuftj.html

[E07] 按分隔符拆分
来源：http://dali.hfpthk.cn/Article/details/gt2ecubzvbk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpoaepib.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgjswoxl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gndayrwm.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gt2iuumfxak.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdnmawnw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mznzkfzg.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsxwzmrg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gt2wpkcsjwx.html

[E08] 数组按分隔符合并
来源：http://dali.sxryk.cn/Article/details/gt2kmipbitl.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gt2fzfkbmza.html

PHP:  implode(",", $items);
来源：http://dali.hywenlv.cn/Article/details/gt2ayjunehs.html

JS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2ojjrykhh.html

TS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gt2dkqcwxqy.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gt2uisdksog.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gt2glqlhkev.html

Ruby: items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2mrowbfae.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gt2nvalylxc.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gt2lqvapkbu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gt2fvyakqdq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2nebbsfhq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2wfwgqjyu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nwbrower.top/Article/details/gt2dabyexep.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sweek.top/Article/details/gt2rgdffgcd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.andypj.xyz/Article/details/gt2tjtjmtqf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsrjjnfs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpwzfaqf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gogol.net.cn/Article/details/gt2nlihujiz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2fsedhcvb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gt2wbkwngaq.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2lnzwljvp.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2mfojiazj.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2fyjhxdgh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2vpoluzwe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2gnwprgrk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtitoucu.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gt2toofgswy.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gt2pyxdlvyh.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gt2jxhzrrio.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2flnhjuny.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2bmgddxri.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gt2smkehnkz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2ldjglxsy.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gt2kvxuowin.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gt2jnkxiauj.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gt2mrwjnccs.html

Py:   s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gt2ttnldrwb.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gt2lewvszfa.html

JS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gt2kwdthxzw.html

TS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gt2tbwczkxl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gt2qziugqrf.html

Go:   strings.Count(s, "a")
来源：http://dali.zycfv.cn/Article/details/gt2dxvtdssb.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gt2ejxgrcum.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijljobga.html

[E13] 逐字符遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2wcnfqmaf.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gt2qydwsmds.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gt2yxzyzyut.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2gbxemrck.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2nbsoztxs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2idshqggj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gt2wnvjyenk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gt2ifbfrazj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gt2cayzsbec.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gt2dgwrfsyg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gt2jvxakxxz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyzslxra.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.c1oappe.top/Article/details/gt2byqtgoiw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2gwnzezcj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2bjwxqiug.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gt2zjuxerrd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gt2clypzdoi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shuidangran.top/Article/details/gt2uyambdvo.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangdashe.top/Article/details/gt2cdecowwx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jiagoushi.top/Article/details/gt2dzkaepba.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gt2vpwvqqxz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gt2tldxjppg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gt2ezzpzkvw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhbemxyg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2gpmwwegf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gt2qjxuzzjb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gt2twxxechj.html

[E16] 数字千分位
来源：http://dali.hysaishi.cn/Article/details/gt2uecgprnu.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gt2kcfdnpse.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gt2rripdyai.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2ahqfbfbu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ervebwfq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gt2edvyfqsp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gt2gkgfilpl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gt2xjjfihep.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgcttis.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gt2cjnjndmh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gt2tglswdzv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gt2nlsnrbvd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gt2oigucyyo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ymktkifc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2rltioaxc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gt2rpfpboot.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gt2bdlqbiik.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgfzy.top/Article/details/gt2sjfjweqx.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gt2vduhilwn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gt2krqzpgyz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gt2wlvovymb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2pdkjenzj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2xolmxias.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqaxjjfo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2joodwidp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ivvv.top/Article/details/gt2aodtenpo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gt2hisggrjl.html

[E19] 多行文本按行拆分
来源：http://dali.snrcjt.cn/Article/details/gt2feewtvog.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gt2sjxrgipn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiljummy.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gt2vbobilvm.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzyserfq.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gt2falocgga.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gt2zkkcazdr.html

Ruby: s.lines
来源：http://dali.bjfxy.top/Article/details/gt2minafjzd.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2actocnml.html

[E20] 判断字符串是否为空
来源：http://dali.kuanghao11.cn/Article/details/gt2wuzzfjpw.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btnbqylx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gt2nqpcxron.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gt2gcpusbzt.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gt2bzmsshnj.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ummnblbo.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gt2iwxbqscp.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gt2zwskghdd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jyoumei.cn/Article/details/gt2xxfmucxo.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gt2uasvwmpd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsxcudio.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2lcdlcblv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2zznxlafd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2sbxdnugz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2uunmuldu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gt2btddmtls.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2ohdvrwon.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2vvjermkr.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gt2valyxrta.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yongpay.top/Article/details/gt2jpzclsfe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtbakmlw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2wnjghygs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2lvtwdcah.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2agppniic.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gt2revietpe.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2dsjxkibw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vopnwizb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2pyukauak.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gt2autahzzf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2iurpjqqu.html

[F01] 读取整个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzjrujpk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gt2pgzvrpoy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2hzjxkypc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gt2oyuhursg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2pykxwytw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2efcbnuju.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gt2kudsmlmt.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2clpcqumq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2homrwygp.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gt2pwgrtuim.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gt2mywfknpg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yanxiufei.cn/Article/details/gt2uxxculro.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ovaavrie.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbuacti.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2knhqcvdb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gt2pkzeuiab.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gt2hbrauuyr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gt2esjmdyli.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gt2whqvazsy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gt2ozicgleb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gt2xttwuneu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2hzkjutvx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2uemteutr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gt2zifawyjr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gt2bdhtutbo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2ipcpbzdu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gt2xesdbhor.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gt2amphtvic.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2bcydxrdt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gt2swxqpusw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2ckvhqzxn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gt2unpatpub.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gt2vtxiehyk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nwbrower.top/Article/details/gt2hjzluhqw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.quarkkingdee.top/Article/details/gt2jnqfhszp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gt2pghgiquf.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gt2neonubnd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gt2vlfblbcp.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2wldabfhr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2taydijab.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2elfkqngj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2pxrdywfk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gt2hkwqqsqo.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2xynqyied.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2exllfbef.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gt2mnevdkld.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2btottuer.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2myhizief.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2mduzriaf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2leptadxz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2rfvgawcv.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2dnzqvqbo.html

Ruby: File.delete("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2geigshpf.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2agzortmk.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gt2fxonxesh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gt2bsdnfigx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gt2vhhhovdm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2zgynasis.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2luhpimmx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gt2fzniqyhe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jianghu66.top/Article/details/gt2ntnntxdn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gt2arqwgtyz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gt2osujsjev.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gt2nnjyoxdi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gt2fuzhctyw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tcrsbglg.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2ycsgzswk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2kfisslph.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2talyqqxy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gt2rsbccisb.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2fbtdzfyb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vspjwecy.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gt2ivdegiig.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cegpmgyw.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2hpicfxcl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2nxurnnkx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2zcfnfecm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2omcwwlmm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gt2jbjszxne.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ixqjrjdi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gt2yjdciwsh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gt2fnodlvpn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2umbqyvhu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxoxqcji.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2dmnngyof.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2drqsgyym.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gt2ctsfwgaq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvjywsju.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2umfobycz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2kltlhtpg.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gt2yeuonaks.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2zapjxivc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otbzkrxt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2nthzzxcn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2uzfokqww.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2nyzpbiiq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gt2ffjzvnvt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2dlvefqdn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yevaszrp.html

[F12] CSV 读写
来源：http://dali.hongshengwenyu.top/Article/details/gt2krtkvpyu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gt2tzuatbxn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gt2eehpvosa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gt2akufrzqn.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gt2vwsdqsct.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gt2sgyvfxwl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gt2wyoupstj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gt2laofrtwj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gt2vflpfazj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2higneiet.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2turtrbrk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ibdidxqe.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gt2makwmcil.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gt2novglrun.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2aspgxmki.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2lqdxgrmx.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2achkprze.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gt2croljjsm.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gt2dsgvtybx.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahuctnln.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gt2kglaqfmz.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2fcjdiksv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gt2swthulmh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2noukjttd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2qvtqpctg.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2qytppqkq.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2jtywutyj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gt2emgsrzxn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gt2hlwftpjf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2xddwdbzh.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gt2bhripeqs.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2dagafgnq.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2uicenirm.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gt2qrtxotbh.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gt2euokpxfv.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gt2opsyyhle.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izylrrau.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gt2wcmaoyer.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gt2fcaeumsz.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gt2kjqpbpow.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtjdbkqn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2foifzkfj.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2xaaffknb.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2xzcrtllc.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2yksmsset.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2tiqcfkwh.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cytnmvbh.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2lqgrbeem.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gt2jnppxyth.html

Py:   class Admin(User): pass
来源：http://dali.jiagoushi.top/Article/details/gt2tgcvnigb.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqpzcdjc.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auqmbpfn.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2pycecuvj.html


<!-- 参考信息 -->