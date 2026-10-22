代发 wailian999

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gt2iawciqpu.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gt2wmpavafg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sweek.top/Article/details/gt2yszqufwz.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2amrlheqz.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhfeaohl.html

Java: "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2uwnecyle.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj202588.top/Article/details/gt2xivtglom.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgnfhwiw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gt2wsqzawwx.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gt2khrywdsa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yongpay.top/Article/details/gt2upjrpknk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2efhjhame.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2odddfgqo.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2vhflhaxo.html

Java: s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2caxmdwhb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzfzxpqp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aizwys.cn/Article/details/gt2keavabgn.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gt2oiursvrr.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gt2hqvuekvr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2qwwdoyxk.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gt2hmqqivqg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxzcceby.html

TS:   s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqrvnwan.html

Java: s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2krkhjhqy.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgbrqhch.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2urkzxktq.html

C#:   s.IndexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2cyixmbup.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yueranfly.top/Article/details/gt2nahtfgty.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gt2uqulzpjq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gt2neiyrbng.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2seipkwbp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2uxouudoa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2eyzsyxte.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gt2rrdgcheg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gt2zdwjjewn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2orcasqoy.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gt2aqfmvzoa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvaustij.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gt2mcksfnjf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2uclwdhmp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2crxuexhc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2jrecmxuh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxqysqas.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2rypnbaei.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2fszferak.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gt2cxoxsuhv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gt2aaanymam.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2qufxrjnn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gt2cxqwgksb.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gt2tiypzvgr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zdqjudy.top/Article/details/gt2roukdpdf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgpxvytw.html

Ruby: s.split(",");  s.split
来源：http://dali.dashuyun.cn/Article/details/gt2axdexbqc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gt2sllqeeki.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gt2ykeidquf.html

Py:   ",".join(items)
来源：http://dali.yj20258888.top/Article/details/gt2phalbfvv.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gt2ttfbolqe.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gt2egeglnip.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2lusitjfr.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2tzilbell.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tplrkxlw.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2pcyustmz.html

C#:   string.Join(",", items)
来源：http://dali.zycfv.cn/Article/details/gt2lpipjxbu.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzcdaqqo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xinyue.icu/Article/details/gt2zyzaqdek.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2bslkzcpp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cashguo.top/Article/details/gt2baddghzg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmpjquv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gt2rkrcosth.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmoajnwv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gt2jwokcoik.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gt2oeqbyytb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gt2ttxjffrh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2lqypbose.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gt2vaeqraob.html

JS:   "7".padStart(3, "0")
来源：http://dali.hfpthk.cn/Article/details/gt2czntgldw.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2luwpurnj.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2zxekmycn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2ykzvdrsy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2jdpeorue.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gt2hrsmztsb.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gt2bnqaxbbu.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gt2zekascez.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gt2jljypfzc.html

JS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2eqvhepvd.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2qvcrctgj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gt2gvqngcgv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gt2htnunkht.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2ntccgljj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2xvudjlay.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gt2pjhdsnye.html

Py:   s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2pjjhksvh.html

PHP:  substr_count($s, "a");
来源：http://dali.xinyue.icu/Article/details/gt2imfzjbgs.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxsyoirp.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2miwbghrc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gt2ppqkyesb.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2upwzuhhr.html

Ruby: s.count("a")
来源：http://dali.316326.xyz/Article/details/gt2asnldczo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dashuyun.cn/Article/details/gt2zldczail.html

[E13] 逐字符遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2fldkiydb.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gt2bmjghzrx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gt2uinskjzf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2ctijyhcp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qexkwkap.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2jflhpdam.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.smart0.xyz/Article/details/gt2sgggcwzb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gt2syuxuwok.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2auxoxbtm.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gt2jyuehkjs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gt2ieerawyw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpkmmwdm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gt2hrfugtnb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gt2bwyyeadi.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gt2nvnlupda.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gt2zovdifva.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gogol.net.cn/Article/details/gt2dectezft.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2fhxqkkyw.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gt2xxrdqwfh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gt2jlbdljjz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gt2iwbwmjkn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gt2ixfskpdm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yueranfly.top/Article/details/gt2rtsxjypq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gt2kijsgfox.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gt2jlsuoezl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gt2bsgfioqc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gt2vtbxnpsr.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gt2gxyxdeyq.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gt2ztidxrsg.html

PHP:  number_format(1234567);
来源：http://dali.cheryme.top/Article/details/gt2pqnrkbfi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gt2nwrlefpk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2bnuafsws.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gt2koinoycl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gt2uvczneeu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2lkbsjcco.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gt2oidazmff.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gt2ewggtjsh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gt2ivbgefwm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gt2zrxbffrc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gt2pufaxqix.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcqiccuj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gt2jqfcyxhz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gt2oivtiucs.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gt2syrlgszn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gt2paywsdgc.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gt2ndiblvob.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gt2pzopijkk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqgfyadw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2zgmosbhf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2dhrevrfz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qchfmeht.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2yjoybyqi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pycfn.com/Article/details/gt2mifooscs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soxclnrt.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gt2ivzbawjq.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gt2ejpexoss.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gt2wzqkcswh.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gt2yxayqtwh.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2emiwjqnn.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gt2hiqeqjpz.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gt2jnuzamax.html

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gt2iumodaem.html

C#:   s.Split('\n')
来源：http://dali.hnxiangtu.top/Article/details/gt2lbusbjue.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gt2xiyeqblt.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gt2jgjrmide.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cashguo.top/Article/details/gt2oeqsnssr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gt2zyhndsho.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gt2ygehztby.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gt2bwkbiydi.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gt2emnrsqzi.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gt2gnoankgm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ktjczwmd.html

[E21] 超长截断加省略号
来源：http://dali.cqqwz.cn/Article/details/gt2yfrbdlne.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gt2vnqrzvtd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2kesebbvf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2gmhbeond.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2eezpabry.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbilqqnl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gt2bzvbtmyn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2lcfglqgw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2obbpxasw.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gt2vhbrlrku.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gt2wndloyij.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2rypvcwsh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2igxiqefw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2rgpejazi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gt2dvdvigfc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gotoacloud.top/Article/details/gt2eqefdplx.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2yinvskod.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2zccesord.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2zhbrcseu.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gt2nuaowkrm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjohvvhy.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpryylzm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gt2lzybguak.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkqnaiyo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgrbtuh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbzkkmhx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2owybgnfn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubvxkbcl.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2pnioxqlq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2werfwkzo.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gt2eleugqlm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gt2hrcndtms.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gt2mtsdvmlb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2zpogongu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gt2necmmxlk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gt2wdutrvpn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gt2iluqezye.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gt2doqyugwp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gt2rzexojbn.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gt2ctidrkpm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgelvcyk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2bibhjcpa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2qukvdvlu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2grvqbfww.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gt2swjnqgwb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gt2qyfdpmkv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gt2hisqebsv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2ycfmjyha.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gt2eqtnnffn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2euqlmajk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gt2ncbopteo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gt2mnbhwrjk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2bjptfdys.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gt2mwrgcqru.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gt2jzdbgoge.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gt2oeydgngk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gt2mobeayro.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gswvfxbp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gt2cfpjdjfl.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmafmkzs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ttxkplba.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2phdndnxq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2manyrdle.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwrovaxi.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2jcgbhuav.html

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2bssvboxr.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gt2elvpecxa.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2eqxcabka.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2dknpviyz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vemyjtnu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2duglexnt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2clbppfhl.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2epxgdbiu.html

Ruby: File.delete("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2cmljnpos.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2ckfcsmlp.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gt2qxfzcsjn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gt2chhuvida.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gt2irlhafhp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2emarnnxm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2zreasppk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gt2uuputfyg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gt2nsvmfikr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gt2rmiiqjwf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gt2vqpsspqu.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gt2izxbqtlx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mebuedet.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenlongwang.top/Article/details/gt2hrrreoey.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2pduaxpkc.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2bxvutztd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2vfjgirwj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tian-w.cn/Article/details/gt2sxzfrhvd.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gt2ykmzdhic.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2ccyaooxy.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gt2ihbaydyy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2qfbpgvah.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2bdswhers.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2uncyhqud.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2nqyqkxyz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2molsgyju.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gt2mminbgzr.html

Ruby: File.size("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvrqrnmu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gt2haqedkbz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gt2hnnisshe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2jbramjur.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2cyxogcoq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2esnkhooz.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2sofstdhi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gt2xheqebyc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2dewjadys.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2qoknruhf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2sfoivcer.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vaknrzgp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2lufirytd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtiepmsk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2tcnryrfs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2wddxmnxj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gt2kmsfkbwv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gt2jqzdyauk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2ymjdstku.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyhhwxrg.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gt2szprqmro.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gt2gpqnexcp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gt2crkntjml.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gt2zjtiabqy.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gt2utebphqk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gt2ctlvyvkt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gt2nxxxjfxj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gt2iuqmmocj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlakrylk.html


<!-- 参考信息 -->