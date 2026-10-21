代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gtgflvpgen.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gtahntnyoo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sweek.top/Article/details/gtfrdhppju.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gtaiuodvdm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gtrtxnoniv.html

PHP:  implode(", ", $arr);
来源：http://dali.ivvv.top/Article/details/gtuaarctdr.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtjvlgatxt.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqoxtbdm.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncqqfckc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gtgmespkrk.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtqjsrxrvq.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gtanfilxjm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlqudrors.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtstjfrzlq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbzbnsmav.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtjnkwavgl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gtovwamiup.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gtbbocrrip.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtknhaoxtk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtfewzqgti.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinghuilouyu.cn/Article/details/gthhilzqkz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gtufwxhggz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtqpqzvggj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtimsqyqfn.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtaohkakia.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtwkyytzqz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gtmhnatgjh.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtcxpwaxlh.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtxbtxeuag.html

Java: "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtojqrsjgs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvliblhbh.html

Ruby: "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gtkoytrvjd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gthyqaaatj.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtqwfjogjq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenjidiqi.icu/Article/details/gttmeeyknr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtiamkkdbb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtcjaazune.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtagzvwbap.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtsnqrntsx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtstbuepoo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.havefunace.top/Article/details/gtxaffhgpo.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gttdiybgnk.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtqysftldx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtsiujkaxx.html

PHP:  strpos($s, "x");
来源：http://dali.dianchejie.cn/Article/details/gtwyilikhp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtmnsjeiyt.html

TS:   s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtlpokicvz.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtwinfmkan.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gtvlghgdha.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtgiltslbm.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtwbvxdcql.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gtrgjfascq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtbihmszic.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcfjshju.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtcthlihgw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangdashe.top/Article/details/gtrprmmips.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtnfouqpup.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gtahdbrrhd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gtrflvpssc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtthobkomg.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gtorjnmyii.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtmgmwtitq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gtbegiszjm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtgmnrtywo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtpdjagxid.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtwdqpkesv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gthapwslry.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtxkuhjfpm.html

C#:   s.Replace("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtfkrxasas.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gttpfrkrzb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aizwys.cn/Article/details/gtlzdomtzy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gticezkcib.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gtksnivydc.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtnonyywep.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqjytxhc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gtsdciwqgv.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gtqmhgjbvw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aibaodan.cn/Article/details/gtldkpdtpm.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gtjmuznlkp.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gthuwshkbp.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtulcjmxpp.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtfmeqkedc.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtmtoiuzmr.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtsotnssev.html

Go:   strings.Join(items, ",")
来源：http://dali.fzhhl.top/Article/details/gtdlucazzy.html

Ruby: items.join(",")
来源：http://dali.sweek.top/Article/details/gtmacusfcf.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtdnqzmfrt.html

[E09] 去除所有空白字符
来源：http://dali.redwolf501.top/Article/details/gtvkactyhk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gtfqsuorty.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gtxrvjlizk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtcnafplvb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gthrflpsid.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtahioksiz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gtvxbivodx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtqizhkwhb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gtapfppkgt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gtdzabkkeo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtfnihjaym.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtsdnovibv.html

JS:   "7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtdlocakel.html

TS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtbhwbcbnw.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtsbictzca.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtlgqexhpg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gthoijrijs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gtquuvqipc.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gtywrxxkjw.html

Py:   s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gteyegihih.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtluodvtth.html

JS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlljjlmjm.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtsullqxcj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gtazslsslb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtgvhvfaqa.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtpaubdzbt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtckfmldka.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtesrmynqa.html

Py:   s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfvotexh.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gtwkncxusx.html

JS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtxbsqlscx.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtcursmtqb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.meibo888.top/Article/details/gtboqksltg.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtofwjlsfl.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudjedrex.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwevoubpd.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtkoxoidil.html

Py:   for ch in s: print(ch)
来源：http://dali.shzxlz.cn/Article/details/gtmpdvhgiu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ydzc1.top/Article/details/gteerxxnhr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtimvtofce.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtggypzrsc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtnkdmiqus.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gtifmibsve.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtbewbpibv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gtuwosxqui.html

[E14] URL 编码与 Base64
来源：http://dali.zhongyouzk.top/Article/details/gtobsrxqpu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gtxehwpphb.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gtoydlsnfk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtbtlaxeoo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gtedibcgxp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pycfn.com/Article/details/gtvsqureqo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gtdvyjkaya.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gtatzypsae.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtnnlqyxfy.html

[E15] HTML 转义 / 反转义
来源：http://dali.aizwys.cn/Article/details/gtbxjfcupq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gtsquyxwfh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvzhkjuoy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258.top/Article/details/gtlwfrlsuz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hysaishi.cn/Article/details/gtgrcmhzwr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gtcbvytbxh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgseoqoyy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gthmxjfrlh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gtgwnkjpuw.html

[E16] 数字千分位
来源：http://dali.fengsongda.top/Article/details/gtfvnyuuju.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtyhvevito.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtzwuaimyu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtsvodylfi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtpmlexenn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gtrtvhnjxg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtrqzuvrea.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtaoxgakhe.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtzruelmws.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gtppbxnhch.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtlwifhqed.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gtthrmixdq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtfyzcgdzl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtcrmreujm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gticwzbuhv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cashguo.top/Article/details/gtuqnwirak.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gtlluudxjc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtgscxfrqa.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfazyswx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffegcwkv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtmofkaxje.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtqdwonkgz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtxdfvagrz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gteknsgbcx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtkrqlhteh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtdowvrfet.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtyzatyfhq.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtpmtsnhns.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gtkypnekun.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gtcxqssdzv.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtbqylwuor.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtxpwiqgfr.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gtwtwrnbcz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtofuxzgoy.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gtcfzsakct.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtbtchmyfd.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gtqvrplhqs.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gtfcrkmmwr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gttlppfuzs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gtxlaipmky.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gtnyhipmnb.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtqgtxbzrt.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gtjvsaqfbc.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtvfnfqkjs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqkjvymok.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gtknbhdcub.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtdwvxfzee.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtclwqttsx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtadqazpvr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtfavcdkyx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gthrakqmva.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guowangkeji.top/Article/details/gtkcfzhrev.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtcqafpcih.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtchkotoia.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gtizzgcarf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjcjykea.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtvjwsknbf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gtznqgkwzc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gthkgnhuqq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtepmnvfpq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gtilzcakuh.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtwgqzoamv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtjibzcqdh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtanfrpsdj.html

F. 文件与目录
来源：http://dali.andypj.xyz/Article/details/gtmvgjvsxm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtbyityikp.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqzbggex.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.snrcjt.cn/Article/details/gtvvfvqazt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtkjxgerfa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gtekudwdun.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtstdzhxan.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtyrytjydq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtbvseocck.html

Ruby: File.read("a.txt")
来源：http://dali.cheryme.top/Article/details/gtymtlpyua.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnbkgeecy.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gttgziwiuw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtwjxhyefu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtfkjhqwuq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gttqnvycng.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtxbyrdjum.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gttdpvzzyj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gtgcvcivhy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtnjvswukq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gtaviahenh.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtjzewlewf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gtccrnlnmu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtinmfazjg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtnxnzpcra.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtsyoyizwn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gtcmufhswe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gtprtamwld.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtizkeeltn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtxujnkqzj.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gtnvkzgbzg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtnzkgenhd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gtvoagtdfy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtatgksfza.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtaszeulrh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gtefparodd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtkojwqhsy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtzymfkfco.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtnyoaspqe.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpjtttks.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtcuwhbpms.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtffihvojv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gthvilwuph.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtqucfacff.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtntwmihdm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtinmlwoxg.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtysvxyobx.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtbfjboobe.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtqgojhzdp.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtijzjwghb.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtithozblu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtgpmlxrav.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsszevyg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtfaeaefmx.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtkjyrnccq.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtipheuxyg.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtqfxxenfz.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtqpyowpcc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gtcihugpcd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhoulong.xyz/Article/details/gtfrlwpbmm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtvrunzhan.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtyfueylty.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqlkdosh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gtwmsvipis.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gaohongyu789.top/Article/details/gtpfhjncab.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtfsydoutl.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtcpfrfcun.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtgozvlhsp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gtcdnxprfz.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtxswdhprc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtlmnvecdq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtuiootriu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gtthcppxpq.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtpfmmbqrt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gtnagsyzkm.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtlsvdusxd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyarbptz.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gttjjlcyks.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtstzwwdro.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtjnxaclkt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtldtsslst.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnglpsekj.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtnnxallbl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gtfuklihqk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gtlzhmydul.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtitzwosnk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkszmwime.html


<!-- 参考信息 -->