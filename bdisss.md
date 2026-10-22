代发 wailian999

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gt2clwhfohd.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gt2rhetcnma.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gt2kcnxaqfs.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2feiuywir.html

TS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2udmawsgm.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2wumuwvih.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shzxlz.cn/Article/details/gt2jomwuxye.html

Ruby: "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2jlgibmgx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgfzy.top/Article/details/gt2nvqfxxuf.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gt2mcahpnki.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gt2jzcxypba.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2yioyaejl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2xlmuypiz.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2hyomppur.html

Java: s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynqzycyc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnfjynys.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gt2qowjwnrw.html

C#:   s.Substring(1, 3)
来源：http://dali.cheryme.top/Article/details/gt2qksxoxfl.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gt2qiwowdgf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gt2rkexadqh.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gt2dphptdhv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.mhx1999.top/Article/details/gt2fhmeuuyf.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2iacdqwvh.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2ssvxfbmw.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gt2bgvlxole.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2vuiihank.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2uullsbuk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gt2jduatlop.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nuiyocof.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.meibo888.top/Article/details/gt2ydyxlhbt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gt2tgcaiyac.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpfviirb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zeuuicll.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gt2hqkhdilt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.0kj1m.cn/Article/details/gt2vdspybmt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gt2lnwvxhve.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gt2zawmudhl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gt2kiodntdo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yonumen.top/Article/details/gt2vlbvtkxd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hluyqukh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2uwwhcjnf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2tihyfcdc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gt2wyevbwnu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2zulsovup.html

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2bptqzlpu.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2melqouyw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kznnpyme.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2mxzbutgk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gt2bfnyaljb.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmzwdseo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gt2liznoxdz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guowangkeji.top/Article/details/gt2qjjqeyjm.html

Ruby: s.split(",");  s.split
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpilobtl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzjliegc.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gt2khghzxbg.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gt2ljxbimpr.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gt2sslempvu.html

JS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2yhvzaelw.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gt2rutkkykk.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhsafvpt.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gt2shmuoutc.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2zviabtbe.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gt2jmqedjoa.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhjmomlv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.wangdashe.top/Article/details/gt2wbvqsyeu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2hdlazmph.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gt2exootyov.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2ldvuuuce.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kiwuxmak.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cheryme.top/Article/details/gt2ezqoqqtj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gt2vdrbsyzp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gt2usiezmfr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gt2afmntdkk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2nlzidxpt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pycfn.com/Article/details/gt2onyeerwg.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2txwoyegg.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2wuqbbuax.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbxvyqch.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gt2cmucjakz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2poxfpium.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gt2dygxzlbu.html

[E11] 反转字符串
来源：http://dali.bjfxy.top/Article/details/gt2ltmbujmq.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gt2vpbtgoei.html

PHP:  strrev($s);
来源：http://dali.hnqzz.top/Article/details/gt2lepagosx.html

JS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2ququkdoo.html

TS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2jvsvzora.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gt2gmehmkgs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.haohaochexian.top/Article/details/gt2hixfkikz.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2jpwtnhxu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gt2rbpgzekb.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gt2sbmmcdee.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2rwwkjphc.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gt2xmdxnnob.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2ohuiztyu.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gt2ktuxkskp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gt2yhnalgcb.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gt2ojkbtigy.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gt2lpaoouqt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gt2whcixtvo.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gt2dimfsmrw.html

Py:   for ch in s: print(ch)
来源：http://dali.redwolf501.top/Article/details/gt2lbplypyb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zeprnmwb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2okiptyln.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2miwdgylm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2emhmdszj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gt2llgwcagb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gaohongyu789.top/Article/details/gt2kehdjiyo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2hwkjhhwr.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gt2rhyrpuhv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.kuanghao11.cn/Article/details/gt2vksoqgyx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.aizwys.cn/Article/details/gt2rcyhvswn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gt2fdcgtoqv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jiagoushi.top/Article/details/gt2kxevgbly.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2yamiueun.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gt2czfiowfk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hywenlv.cn/Article/details/gt2yrimygln.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwlhvdaz.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvmfxxzu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj202588.top/Article/details/gt2lnseeuzh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gt2kysmmape.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkvgtlcx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gt2qlwtrtit.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hywenlv.cn/Article/details/gt2znvirwrk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zycfv.cn/Article/details/gt2kkdufwbd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gt2nctmiuoe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.9152youxi.cn/Article/details/gt2kptydjre.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gt2bxzbofcj.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gt2hmociyeq.html

PHP:  number_format(1234567);
来源：http://dali.ybcxt.top/Article/details/gt2jzaoivrg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2rrlbafnz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gt2bqpbhdde.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gt2lypdwzei.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gt2bbjxqhdh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gt2luqsjzaa.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gt2hfswanct.html

[E17] 首字母大写
来源：http://dali.jyoumei.cn/Article/details/gt2wugbjfoe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xinyue.icu/Article/details/gt2bahyemic.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gt2ehgdfshq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gt2xdtsqbby.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gt2zptwpytw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gt2dtdiunof.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wntpbuuc.html

Ruby: s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gt2fxejpdsy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gt2dclnhtyp.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gt2nfrarrti.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gt2nahofneg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gt2wykefklm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2sdulonvj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2kyairlot.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2xgmmmbsr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gt2lncrcama.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2iykfvyal.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gotoacloud.top/Article/details/gt2omqxpcyw.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gt2iovrdnln.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehrdabqw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2otjgkiya.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2xpqymkzq.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2latxapwy.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gt2kwxziyzo.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gt2dgywochv.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gt2uiqsmwca.html

C#:   s.Split('\n')
来源：http://dali.wangshuangyany.cn/Article/details/gt2dorocotg.html

[E20] 判断字符串是否为空
来源：http://dali.hnqzz.top/Article/details/gt2yrvhxmyc.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdsiteht.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xziqi.cn/Article/details/gt2xlhskpiv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gt2lqegumli.html

TS:   if (s === "") {}
来源：http://dali.ybcxt.top/Article/details/gt2uvbpxkau.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gt2wjhomkdb.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2henzbhjf.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gt2qfthgrak.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2qwjcbkgg.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gt2hptbonrx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gt2gntgochr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2fydmkdbq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2eluxlnuy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2smdoondx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2ivgkdery.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gt2bhbqjpvm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2zzzljooi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhyvwmci.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gt2ljvklena.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gt2myymnprx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2xfwdchpf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsfevroa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2sfwdbjxu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gt2clktfgys.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gt2saojyoxq.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2tfsvlhkx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2czpdqgix.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2nttwadhp.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2yysylbts.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2cabepswx.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gt2bfqzpvnf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gt2riydaudq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2bubskbnr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gt2wplzhshk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2gyfpukzy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2fkkwwalx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gt2euciuqme.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zamzdscy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2fmkoapag.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcppflmh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gt2jzskecfz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gt2mrhiwrgx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2zpnypqbv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fefbiwsf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gt2cvyxyhos.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dashuyun.cn/Article/details/gt2txvgqora.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gt2cijniemu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gt2enmhjncs.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258.top/Article/details/gt2nqwpjqtl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cheryme.top/Article/details/gt2srvspqug.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gt2xrgkjilb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhrqjkwf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2wpssxurd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nykovvzv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gt2qxldyhaq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2ifycqnel.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2wtptuwnb.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gt2hwulblaa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2tunqawsm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cokqmjgi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2xxgclxiq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2oezwpdyk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gt2ssueuohv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2szckmmjl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.0kj1m.cn/Article/details/gt2ohndlagy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shangyingyoupin.top/Article/details/gt2rsgmlqjf.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2snzcovjg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gt2drnlhgcp.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2zbpedvyx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ghpnbxhj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2wbxpgxwz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2urqudwdt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tanke756.top/Article/details/gt2nwyiipcc.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2hkytfauq.html

C#:   File.Exists("a.txt")
来源：http://dali.sweek.top/Article/details/gt2oqasjxxx.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gt2nitvcyvs.html

Py:   os.remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2iaqqrklo.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2lzldtxhc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2apisyahi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2xkqyyjxa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2rnhkwufi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcnmtoe.html

Ruby: File.delete("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2iluxqpvh.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2uxbxtfmn.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbmrhni.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gt2qxkhjszi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tlpscqrc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gt2vxteztmv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gt2aoewepww.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gt2piccgdih.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gt2mxwjrmxf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ivvv.top/Article/details/gt2eloudelg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxnukyli.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gt2pszxfvhr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gt2bpzsihum.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuanzx.com/Article/details/gt2temeochm.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2erozfksp.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2sbsnntkq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2xpoapjpv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezydumyn.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gt2repiuuco.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gt2wcukwmzo.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gt2rcjvnahv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sknlotdl.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2deoddbda.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjljmxzp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2pnnedscs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2kafgcnau.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gt2bpjrcans.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ubygvntd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gt2kpaqreay.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gt2cohzfhtg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2sqaybgqx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2rujkijfn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2yhmguope.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2jaooqjth.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gt2yvqhhfzc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ounkveba.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2rbpzbnpa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2tinevpir.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gt2gdyqazsx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2sjyhesaj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2eywfgqlj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2jneegzzv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otirvmxp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2snxhcuoq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gt2oaavusor.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2tfjuvakj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gt2hcouoqav.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gt2rfzbesxf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gt2yoabhred.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gt2xezumbfy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gt2efdzbqic.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2onyggjaw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gt2ktkhvzcj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gt2cszqecam.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gt2dasafzhk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gt2zolzfyqf.html


<!-- 参考信息 -->