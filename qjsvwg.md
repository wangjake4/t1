代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2pjkhepmf.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2mqcvpeci.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgfzy.top/Article/details/gt2imlsnzma.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rzyinhbj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2ogqhwukz.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2rmyuauju.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gt2abxpwrmk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gt2fkbzcaaq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shzxlz.cn/Article/details/gt2erqcwiqf.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gt2fxqnlvmt.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gt2orsyshnh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gt2utdjnjvd.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gt2wdygnxjn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gt2sfucumxk.html

TS:   s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2icczxmqe.html

Java: s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2sipfvdtq.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gt2qdvsvdme.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gt2umcboyop.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2lcdemotq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenlongwang.top/Article/details/gt2juvarsca.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gt2fscjqkto.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jyoumei.cn/Article/details/gt2aqhoktzk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2kcvftfih.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gt2eledvoko.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2veksjygv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gt2bnznwtdr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yvedp.cn/Article/details/gt2yxvpscls.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2iehcyhux.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gt2gxaxzxmp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gt2hpzhjsqs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gt2cijsdtmq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2cozmspjq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2xqujilwl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2wvvnpgpw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2qkclwdlw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2zpcuvmiz.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2qfnsmepx.html

[E07] 按分隔符拆分
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqmslkuz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmgotcdq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zkxfpjai.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xziqi.cn/Article/details/gt2jtigdifn.html

TS:   s.split(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2bgsvkscf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uflfxdbl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tanke756.top/Article/details/gt2yyhqgikn.html

Ruby: s.split(",");  s.split
来源：http://dali.yongpay.top/Article/details/gt2ghzuudsy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gt2pycpthfw.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gt2zfzelifl.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gt2fajcdmwy.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gt2zwzubyin.html

JS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gt2yttrkbfx.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gt2succzijc.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gt2yfzfogyp.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gt2fpwbfvfm.html

Ruby: items.join(",")
来源：http://dali.cashguo.top/Article/details/gt2lqfkdfno.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gt2ordgovwf.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gt2cbtutqhc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2igompotk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggzjtxav.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2fgrwqwor.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxwqkqlp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gt2djkqiydm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gt2kylqgwht.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gt2njaiefvw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gt2pbbzoqxi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj202588.top/Article/details/gt2zdrmdxnp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2hepvnyes.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zckgsbsr.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2vcylwzhq.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2arqbpmva.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2zcceiajr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2mqspiwid.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2xhdlczoo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gt2pycpyyyi.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2cwtsthtt.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gt2yglqzexx.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gt2nvjdieiu.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2tgqetyhs.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2qfesmnuv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gt2xlahhvxg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2tdctcovc.html

Ruby: s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2kwozafft.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxbdqtmj.html

[E12] 统计某字符出现次数
来源：http://dali.chenzaomai.com/Article/details/gt2sdfhikpm.html

Py:   s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gt2nhnffulo.html

PHP:  substr_count($s, "a");
来源：http://dali.xziqi.cn/Article/details/gt2sxhluqqo.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gt2zeykddhq.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2krfkbdfk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zdqjudy.top/Article/details/gt2plfwahmz.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gt2kstdedjf.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2sqxxlosk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenzaomai.com/Article/details/gt2frjwpxnt.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gt2isyarbpy.html

Py:   for ch in s: print(ch)
来源：http://dali.tianlin.xyz/Article/details/gt2hftlfvzg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xziqi.cn/Article/details/gt2hycrcrpw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gt2jtibtsfl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2korymabf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2ktvkxnin.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.smart0.xyz/Article/details/gt2tacxisrh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gt2ltqkitri.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2lcyxrkrf.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gt2sdjfuvzt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzugwtif.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gt2cxzgfpem.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yonumen.top/Article/details/gt2jryeehad.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aizwys.cn/Article/details/gt2vlxvmzde.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzgqpdwz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gt2oowerkok.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zdqjudy.top/Article/details/gt2fiavrwan.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gt2tmozdiax.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdabcyfn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsdbejfl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2ibfvuoyq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gt2myiaqivu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gt2lilzyqwy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258.top/Article/details/gt2caldxkvl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gt2hhjzfqcu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opiuzewr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gt2sbdignwp.html

[E16] 数字千分位
来源：http://dali.snrcjt.cn/Article/details/gt2fvhzayin.html

Py:   f"{1234567:,}"
来源：http://dali.aizwys.cn/Article/details/gt2xnzczibp.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gt2cbrpatlf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gt2znkpqpeg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2bvmzgfql.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gt2ruslttyp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gt2kcmqqcyt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yongpay.top/Article/details/gt2dnpeipgp.html

C#:   1234567.ToString("N0")
来源：http://dali.meibo888.top/Article/details/gt2stxqsmpv.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gt2xwzgpuij.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gt2mwansqtw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyvpihdm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgdavpin.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gt2xtcvxuwh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gt2eyqhxupw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2rsjrkfjz.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gt2ehdacxfv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gt2wlyxgaoz.html

[E18] 模板占位符替换
来源：http://dali.tanke756.top/Article/details/gt2bgqdvmtd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gt2dmkjkyge.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqfdgvjl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2xkcrwyao.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2iptmcowo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqshtvik.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2aymbvdyr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gt2woqbtqyf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gt2vwkmybtk.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gt2ffjqncit.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gt2twqsutjk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.havefunace.top/Article/details/gt2iqlkdski.html

JS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qiuzzxxd.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2ygikasyu.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gt2kcvdcrig.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gt2zxopgycj.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gt2uvelgnbm.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gt2ppoppxjm.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gt2whbyrhpz.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gt2mdsevdpg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.kuanghao11.cn/Article/details/gt2imylbdor.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wjmydlsj.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gt2cebujmhr.html

Java: if (s.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gt2pinsbjla.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gt2bvxlhtgd.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gt2uvwnhwme.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gt2nuqxtvza.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfxrlmg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hammf.cn/Article/details/gt2wauvwjca.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhuwkkts.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2ujxrxeis.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2mnqrzzdw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2nahrvyld.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddzxhtsl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2bnlaseaf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2amrtfhzl.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gt2pgdlafaj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pycfn.com/Article/details/gt2rxrluuad.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2gcxlunpj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2swyfdbpv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gt2kdfsbgko.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gt2llyzsjja.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gt2svovsbkt.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2wvrhlben.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxijmptc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2gskzkagz.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gt2tktrvxic.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pnerabbc.html

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2zzyopshr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gt2rcgmlici.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2avwqnend.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gt2fxflkzha.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gt2kytndtoh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2toekpmik.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gt2qthhyxcs.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2yourbzkj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2omymotup.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gt2duymicgq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gt2uilqzofy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gt2ofbcgplb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2fkktiblo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gt2rcryegxt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2yjzlfgtl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gt2lsnnfmhw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuxming.cn/Article/details/gt2ozxrraxw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gt2gdilqjoo.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gt2nkdyuhyx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gt2bsljxhcs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2laqateiq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2dtrgqstz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gt2mtfbliqt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gt2ateidpog.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gt2igdmwqfo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gt2jzszwwyz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2qkkoxzbj.html

[F04] 追加写入文件
来源：http://dali.sysykeji.top/Article/details/gt2hbfgfrnr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kartsbvd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gt2bfdpcdcx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2bdhxrvcr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gt2qtbompnz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gt2mmxttaaj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvmqmcwj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gt2oxcyheps.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqbxznnp.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2tejatskb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gt2nxmzduht.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2cimnydsz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2zzveeamc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2ygkpgajt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2rylposfl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vpnayxlp.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ffqymmws.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2wpponxqx.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gt2yxkirsmk.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2qsiuwjju.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpmwfzvt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2nkiugjhd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2vcjonjrf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2wbwfabvg.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgkmaftz.html

Ruby: File.delete("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvvdilak.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2mbtkqphr.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gt2pkxgyion.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gt2njgekeuv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvjokeo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccqjpjzx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gt2fflmfooj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrrggugo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gt2zaaokrxh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gt2nhnligcn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gt2szimdwka.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gt2fowxtelm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gt2xsqvvnlk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.redwolf501.top/Article/details/gt2uerqpjlt.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gt2tbiljuvh.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2juuxrryk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gt2kgvaggwv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thrqoyxo.html

Ruby: Dir.children("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2dmkrhqce.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2paloqhjx.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gt2zfbthgcb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdyyghg.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2lmjpvvyi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gt2imryktuo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2qttgiubv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2ikkbvsmm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gt2rceicifk.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2pmtnthal.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gt2ihdouufj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gt2iszjkcia.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcamodc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmzxisui.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2dsgnphmu.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2jnepgswu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gt2lrfycxiz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2vfuuapdc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2bvyjcopj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2vvzvolrp.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gt2bcvdcuev.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2mmfbowtl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gt2iiqvkiak.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2diciwopu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2iqggvkql.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2vwnpoigr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gt2qwkghaeu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2gewcvmmn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsfnvjva.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gt2yiezryss.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gt2umqfgrty.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gt2bpbcrrst.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gt2raywpvzx.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stnlhlwy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gt2kydekcxy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gt2jhdkxzbt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gt2valxdenx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gt2vzuhxdvl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2jgqyhaca.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gt2tlrhishi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2badhnznu.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gt2jvbojbkt.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gt2skyteujv.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gt2oopsdpfl.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2silsvakz.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gt2lxzufdob.html


<!-- 参考信息 -->