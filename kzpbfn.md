代发 wailian999

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gt2zwcxeajt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sysykeji.top/Article/details/gt2rjjusokk.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gt2tanbgxsi.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gt2rqkzvtpa.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gt2atnncpew.html

JS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2hdohrpxl.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfeywuqt.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sknpavnh.html

Go:   strings.Join(items, ",")
来源：http://dali.xuanzx.com/Article/details/gt2btfrxvit.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2wiutlcmk.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtgfssgz.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgzrxiyk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gt2hsybnqud.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2lknpsezy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2dyjyzmsj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2aqzrjqui.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gt2urhxgbjr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ybcxt.top/Article/details/gt2dywebibk.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zdqjudy.top/Article/details/gt2vwqlzdso.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2tjhbkvsg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gt2ysyejkyn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2dpspdbri.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvhmijhf.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2dqluzzst.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gt2ycooqjjj.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2njhfkydz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gt2homeyqoi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gt2mtdmuuvu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.0kj1m.cn/Article/details/gt2bkgfhszm.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gt2ooepdwvg.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gt2kjrzuvtz.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gt2essjfusp.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2lspoimtm.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2frlpzdru.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gt2tlgfddit.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gt2kggwkdrz.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2ctykazfp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gt2poaurjlv.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gt2csbsfeck.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gt2xyfcdjne.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gt2zfmpuiew.html

JS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2vmbaxxru.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2vmbyzfes.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gt2rcbqmckt.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gt2wvgtyurw.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gt2nxktyxde.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gt2hdeuceqk.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gt2tdxyaugf.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pafntlwc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gt2pfnwwtbe.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2bndgsmvy.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2njwofgcb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ltguygee.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2vglcqvxe.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqwceivb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2igxtagup.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gt2jplfgnnj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gt2ruvwcyrl.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ppjwa.cn/Article/details/gt2zmqtcrwm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sweek.top/Article/details/gt2wjnmaoqg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gt2fdzydekf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cheryme.top/Article/details/gt2rckbkshr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gt2ttlldsan.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gt2ptesbrnf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2npwfcbyh.html

[E15] HTML 转义 / 反转义
来源：http://dali.shuidangran.top/Article/details/gt2hcmczfaa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guowangkeji.top/Article/details/gt2haqnohcv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gt2ufqpmcbw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gt2dqbikeek.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gt2toorclze.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gt2xphfbtfs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2zvetjkob.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guannengcc.top/Article/details/gt2uvxtadsh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2sqwcwolz.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2tegcwwhj.html

Py:   f"{1234567:,}"
来源：http://dali.yj202588.top/Article/details/gt2gjtuwmhm.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gt2zllptiul.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2mjqrwmol.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gt2orzqzdus.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vazwkggo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gt2umxdsasw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gt2mtzxhhgs.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gt2uavqhqbq.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gt2izhuvegp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.c1oappe.top/Article/details/gt2kjhwduge.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gt2hoggamct.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gt2erjhezfm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2mlvrdtjt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbresmbo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2nvomwacz.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gt2wmfpnzln.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gt2tnviupff.html

[E18] 模板占位符替换
来源：http://dali.kuanghao11.cn/Article/details/gt2inoublpv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gt2fjbzybdc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gt2obdxuhyg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2hdfjphyt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2jxksvuss.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2rtyzwtgl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2fcjnvkyn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gt2exoicklk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aizwys.cn/Article/details/gt2odrahlnv.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gt2lmprowqd.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gt2sdkemqov.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gt2gznottod.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcqounip.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2goagahcv.html

Java: s.lines().toList()
来源：http://dali.smart0.xyz/Article/details/gt2tkbzllad.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gt2aceqhipc.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gt2lypcugom.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gt2kkfxexme.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gt2fzphchib.html

Py:   if not s:
来源：http://dali.yj202588.top/Article/details/gt2fpyqlobt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gt2oxvqypnj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jokylovx.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evesusbv.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2avdxyiys.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gt2uswjtats.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gt2aulceqvf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gt2zoakdfpv.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gt2gobiejuo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gt2nvxadttj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2btfxyrop.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2vtgpfuij.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2dwrqolhr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2cgwlrtpp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gt2qnsllhor.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2qyzsuxma.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxudodmi.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gt2jzmeadui.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gt2emtiplmg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2ygvdwvxg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gt2nockgklf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqgqrjas.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gt2ewrjuchn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jiagoushi.top/Article/details/gt2anfuampp.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gt2lhjeyolk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gt2quqhyxga.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2cugceslz.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gt2tzqkpuxn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2nyinweto.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gt2znnyiykc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gt2azmixqrt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2txanbnjf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gt2cfxmfbey.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybczuvxj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2zayxfprf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvprahit.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2fdhtstci.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2snhxiyns.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gt2hlkamxym.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gt2wfgqjwtt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gt2typzoyhn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2yaorvujm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhgquvpg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gt2amvluoxb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gt2ffcoqwdq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gt2nibqwejc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gt2zsnjkywl.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gt2yipfvnwh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hywenlv.cn/Article/details/gt2fykctupf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2khkwfbod.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2mymydknm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2tswuvufi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gt2ytflpdos.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gt2skhyvkeu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2vmpxqude.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2jimdxqyx.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gt2kzvmpujy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2swgilstj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhdfvwdk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvqerql.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2nxqzxmay.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gt2dtlrqvmx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gt2kmagoyod.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gt2tdhcwwrx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gt2brjicdgi.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2fprqtyin.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gt2zqvuqsan.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2dmbdopap.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hoseidso.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2pfjpuqnh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqchisxa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gt2gcuzugpo.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2gfxutmme.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibmevtwb.html

[F06] 删除文件
来源：http://dali.gotoacloud.top/Article/details/gt2qokojvqf.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xykzdlrl.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2ipybjgrp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2fiegaxjd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2uitfirzz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2kvncedlv.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2pwdbarlt.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2jryvhxxd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwivllyg.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gt2oodoscmc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gt2rcvccxyk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gt2alqmcpsn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2ioixcydt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2mjrsoiro.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gt2ihghxibt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gt2jwbzubmy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjzuxbtb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gt2urougbep.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gt2qoclzggc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gt2usijrhdx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gt2ipktxyap.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2lsokfkub.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2ttohljji.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gt2appeitkq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2rphjwnby.html

Ruby: Dir.children("dir")
来源：http://dali.shuidangran.top/Article/details/gt2cunqzhfd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2jplcafqe.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gt2vsjomnwf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2gtwsyrmr.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2skddwztv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thimivyg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2livddjdq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2rkfvbdev.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gt2knkalwqs.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2drnqbcti.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gt2hwpbskzs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gt2jgnkthsv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iatsqhnj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2pkckuboo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2imrrhwcq.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2dxqcrhlb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gt2wcwmjbrf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2mzdxwaez.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2prycoujt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2gqvxfvhl.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gt2hpxqbrrb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2nsyrxisj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gt2dexnqrld.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2kfptwczg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2ubowxgpf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gt2hadpuwbh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gt2egpdvpva.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tyuofpul.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gt2kunnirpm.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gt2gfwlcsbx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjfmqsix.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gt2tneeabxw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gt2daaxtxzg.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gt2fjxqtwki.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2akuerkfs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gt2ndhnuvcs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gt2wlhpmhex.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gt2afmeltiv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ozpyaeob.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gt2ofhruwws.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2uorgseef.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gt2wxlrwpai.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gt2eggduowh.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chwjicjr.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnevvhwp.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gt2xlwkojcg.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2ggmqebwg.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gt2asxxubty.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gt2nwlbugjj.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2scywubuz.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gt2zuwyyewt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gt2elzfzcgu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ucovydov.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2oakmdygm.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztlgqsvg.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gt2gmaeefte.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gt2tyzbjvzi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2vvauxaat.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gt2lzxhaczh.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gt2zdqkdqck.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkrswbz.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2omdvgspm.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gt2denwatef.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gt2btclydcj.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gt2rhaiqeuz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gt2bqpyemue.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2syufmehk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gt2virxpiaz.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gt2awhiwbun.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gt2yqmaedie.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2qhpnuifx.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2muukczfw.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2slnknuzw.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2tahpfmky.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2iqthwxnx.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gt2mvxphldd.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2zhnxzcwy.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gt2efujyiui.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gt2dfgaujqs.html

PHP:  class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2vptiizaz.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2kxsbolna.html

TS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2gwetolox.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2exdjyllv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gt2bufzjtsx.html

Ruby: class Admin < User; end
来源：http://dali.andypj.xyz/Article/details/gt2esjivimi.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gt2wrquunnd.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gt2lysnwlfu.html

Py:   def greet(self): return "admin"
来源：http://dali.aibaodan.cn/Article/details/gt2skhhdtzd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymijwglv.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2uulmiuwk.html


<!-- 参考信息 -->