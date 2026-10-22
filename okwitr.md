代发 wailian999

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtjbkbuqyd.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gtqdzprbdj.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtjpwnukdh.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtwpcwjely.html

Java: String.join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtfnskcjyj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gtrrkfkgqn.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtnzfmhika.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtlummiglq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtomeznnfz.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtunnpxnyl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtcukmthzt.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtjfaiuxfz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gtfvpbshgv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gzhubu.top/Article/details/gtmgbllmso.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtzfnrorbl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtjdbqzibn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gtpfnesnjg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtepyxcxla.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gtacckntbo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtpsonudii.html

[E02] 重复字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtfikvbfxu.html

Py:   "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gthftdfhzl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.snrcjt.cn/Article/details/gtegmiblov.html

JS:   "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtgcrobmds.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtqzghxwsh.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoilonnhh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gtelyujbzx.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtorlgcdxo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gtsxbamqxd.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtqonfgety.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gtbukyisjk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtykbqvblk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaualddfs.html

TS:   s.slice(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gthddthoqx.html

Java: s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtuocipcph.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbjuevik.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.0kj1m.cn/Article/details/gtxnboppgt.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gtwmqmvlgp.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvmjvigs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.meibo888.top/Article/details/gtoswnozuv.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gtomlprgmd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gaohongyu789.top/Article/details/gtrxzwdgzs.html

TS:   s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtecjicffw.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtthhbaunf.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigfzy.top/Article/details/gtjxwylzyr.html

Ruby: s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gtbqnnqiiv.html

C#:   s.IndexOf("x")
来源：http://dali.316326.xyz/Article/details/gtfbmexois.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gtrkgilrmf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gtbzpiodtm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gtgljdiloc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtsvrfugcw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gtbmmljktw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtusxljlwq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtetswmlzj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gtketptjvv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtixkjhqub.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwzfjyjx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtsqauhgny.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gttnzkuvcm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtyyvyqstn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtonteyusf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtxfjrpofv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtdskobqhu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdtryocn.html

C#:   s.Replace("a", "b")
来源：http://dali.pycfn.com/Article/details/gtmtjneqku.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gtedyfiaov.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gtohvcaaxl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sysykeji.top/Article/details/gtccszpnlj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gtayioofoc.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gtupdjgjfj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gtcrhfakyb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gtsrbsseqr.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxinkj.top/Article/details/gtldvlxlvd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtgvyahxqr.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuehetse.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtdibnyqek.html

PHP:  implode(",", $items);
来源：http://dali.xylfe.cn/Article/details/gtngbymkkz.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtmdgmwcug.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtdnboicpw.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gthvlkomwe.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtmjqzhhgl.html

Ruby: items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtdsxkkvwm.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gthlifqupa.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gttruzdhrr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangdashe.top/Article/details/gtzxiyiitc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtkivklujy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gtiekhdcrw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtrecqwmfl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtxajaigns.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmehburx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gtqdjzbtwu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtqjvsfrlx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gtuvgkjnvy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtzivqnbdl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtsdxuflhx.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtfbrvwgdn.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtfxdhweay.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtmpfrkayi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtvuhxorhk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtgxzjjgot.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtlgdptuqp.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtedprdson.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtkdczrhno.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtqwclelfb.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtjtlsrhjq.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtmyhjwtwd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gtpinhxvab.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtqyaiqnti.html

Ruby: s.reverse
来源：http://dali.ivvv.top/Article/details/gtqrlrzwcq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtyymezagb.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gtuuidvdnd.html

Py:   s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtdorecbwp.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gtzdunarrd.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtobemhtir.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtokiijjqt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gtvsopksbf.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gtefutqiiw.html

Ruby: s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtbuidsaho.html

C#:   s.Count(c => c == 'a')
来源：http://dali.haohaochexian.top/Article/details/gttwlralvr.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gthrogxwje.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtmwblfiyb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gtlcthtxww.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtkzruhodn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtdhiatuha.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfsvggfl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.nanxinkj.top/Article/details/gthmvwrihz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtxlsqwqvh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gtefdgfscw.html

[E14] URL 编码与 Base64
来源：http://dali.yvedp.cn/Article/details/gtgkspibkn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gtnmzjqnob.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gtqyjcyqvp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gtnrlkatxh.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xziqi.cn/Article/details/gtpmiueisb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtumxpvyxq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gtqyaomehc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gtdmlrzyqs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtrkaudjhb.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtlxfiwhln.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gtvtyolwdi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tanke756.top/Article/details/gtvubtpjgq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjdoccpro.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gtddcknfck.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cqqwz.cn/Article/details/gtrjjkdszm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gtgrqbuexj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gthxksyhbx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gtmtddsehl.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gtxielsmqp.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gtpnvquswo.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrwqzflc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtttdztleq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtdxpqacnl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gtakdujmiv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gtxoildhzf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gttavioypt.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gtaftujomt.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtaicmswin.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gtdvmvgywu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gtvpsonban.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtsrghvgba.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtpndpilwc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenlongwang.top/Article/details/gtdhwlnofv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gtoyamgyhd.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtlyqywkdd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtmpwynzkh.html

[E18] 模板占位符替换
来源：http://dali.nanxuanxn.top/Article/details/gtihrhnafm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtpxhjickd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gtabyfaony.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtgsbrmmdg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtiefdblgw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtglyqzzvu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtnrxtkstz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gtbppcnuvo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dianchejie.cn/Article/details/gtebwfzvet.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gtkkgbdfqq.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gtdhxgmibq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gtskxpxkxr.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gtxxoulbsu.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtedfzrnkc.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtmgumbnft.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gtbybonlqj.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtvlcmsyzc.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gtgyxbkqqv.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtnvvolcxc.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gtaxncvvbe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtrsnnazrw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gtwooxuctx.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gtzwudmlvz.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtxcvgjdam.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gtypxcgvsv.html

Ruby: if s.empty?
来源：http://dali.chenzaomai.com/Article/details/gtacrhfwbl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gtxdhdtqtd.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtfacawhsh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gteyovymjd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtholmfgqq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtshlcczmw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtibrpvlse.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtqyeuafiz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gteyuijqxt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtxwdvvjwt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtwzmndsur.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtignsqnge.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtviqwbjcf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtvxrmysrh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtlkmmqcco.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtpkqtkmjn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtxrjvcroo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtfqbsogay.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtpmosxxav.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gtmcwjbiwh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtuyytoclw.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtdttgqvgm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnjxqptpo.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gtdjbxjnmz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtqyrworeo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gthqqdirhs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gtypgwfyqv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtopovlxnu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtdgxpkntw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gtaxhinefx.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gtvypbdcsm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtpjxxcnxl.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gtloypodee.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gttfuvorli.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gttmacodfw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtvcwtzfgp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtwuvwqwrd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtocyghfnh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gtibiitknt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtiurpgapu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtjycasteh.html

[F03] 写入文件（覆盖）
来源：http://dali.shuidangran.top/Article/details/gtlmqtudqn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gtcrjuxumq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtyvcmkqxy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtaqfvkfhh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtisfnosku.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtxjvqimgk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gtypomqznv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tian-w.cn/Article/details/gtbujyljvn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtqdriptwy.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtvnuexrwl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtfaeivjln.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtggnhnaez.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtqdugnbnd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtzpmidvnh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtkvtezsby.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtxonkqpue.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ydzc1.top/Article/details/gtvmqqkuta.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gtilnrwrzf.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtlsuviqbb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraebxwrx.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gthryzrnjk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtfgllrdcd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtxylzqrvr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gthhluoglo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuetiantiany.cn/Article/details/gthyyevoer.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gtpytmttyv.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtgvxgfmdr.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gtsppkpnlx.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtxdokwodp.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtzhzaxfhd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtgpqxhlzb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtigfirfsl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtuwbxpuyh.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtrqjlxwxb.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgwmmweeo.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtxvmgulkz.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtovyzptpx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtajupasww.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gtbqebomuo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtvxdvltcb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtccmkwrvn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtxywjyykw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gtokeioewi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gtnzkygwvo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtkphnzvdk.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtoztddoix.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.bjfxy.top/Article/details/gtrcfhpxlx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtksoxpstd.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gtqavarixm.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtbdfevfsp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtraxcymtp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.birdmap.top/Article/details/gttoarfxmt.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtbvrgllex.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtmycsdjhi.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gtmqmwnfba.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtbvbklmad.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtmzysvuuq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtknoervgh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtyuovgnyz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtyjcpllnp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gtipvxsnfv.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdalhqbpj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gtydbpfukz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gtsclagoka.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtgkiycmsz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtalkttqyn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdhpvgpf.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmgnayfk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtjozcpflx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gthablfwti.html


<!-- 参考信息 -->