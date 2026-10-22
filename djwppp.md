代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gt2gutrnckx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gt2lzgdglxh.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigfzy.top/Article/details/gt2gryntdag.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gt2iazchpxe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenlongwang.top/Article/details/gt2kuhichve.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ydzc1.top/Article/details/gt2vkpcsnxy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gt2obeztqtx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gt2rdpazzoh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gt2uyyhbulp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gt2gjwlmtcl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dymgbejg.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2rqudsxgx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2vacpqqdt.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2rikkuvfk.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2cirtquif.html

TS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2ppejdltu.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2ydhdyzcj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gt2ejtllhfp.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2ndwrgleh.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdapsjce.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ygpbzjsv.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gt2mxermdbh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2uafjgpnc.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2rtjrkhaj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2melhdokg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bazgqkab.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2zuodfvgo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gt2xbvedgyq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gt2kmqdkspg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2ddoduzuq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyycvlqe.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftiafltd.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2exbfqksu.html

Py:   "ab" * 3
来源：http://dali.zdqjudy.top/Article/details/gt2rubqbhml.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gt2ffadimur.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gt2kjyarrsu.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2nejovqob.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2mjxfkvug.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkfjnnll.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gt2hyrujokx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gt2lvnujskk.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gt2afgbzzae.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gt2ncgiennm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2dbailpou.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2okjdwxkr.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2hulidknc.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2rgeeiyge.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gt2lvxlnlwi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gt2nvgznhdq.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gt2luuwoppy.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gt2pymywrce.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxgzmkoi.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gt2nxoamcyg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gt2rvijhuew.html

TS:   s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2iwqywhxx.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2mverzjpj.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gt2ejjhalnk.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gt2gcwgczcy.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2xehoipen.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gt2ykkiogkg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gt2awvnllit.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gt2msvfezja.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2hqlpvdwf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxjdcafj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2vbphiezr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gt2ifcrchym.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cqqwz.cn/Article/details/gt2yidajshd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2sauuxidt.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gt2yvltyynf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2lcapcihv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.guannengcc.top/Article/details/gt2isvqnkmu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2iwamoxak.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2yncwxqgy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gt2amwijlzj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfreizsb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyocjmqv.html

C#:   s.Replace("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2zlcuefmz.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gt2tofhsehs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gt2bxbitrvt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2enbwxokv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gt2ftdfcvrl.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gt2rweqgjmp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gt2sctzrfyo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenzaomai.com/Article/details/gt2kuekrsne.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258888.top/Article/details/gt2udtcpyjt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnqzz.top/Article/details/gt2sxhkzkbx.html

[E08] 数组按分隔符合并
来源：http://dali.gaohongyu789.top/Article/details/gt2sdkxujgj.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gt2ybxxswra.html

PHP:  implode(",", $items);
来源：http://dali.ehwqpu.com/Article/details/gt2zigeivqe.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gt2mpxafooo.html

TS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gt2gtxyiryz.html

Java: String.join(",", items)
来源：http://dali.cashguo.top/Article/details/gt2uwmwgibd.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gt2vbctorwz.html

Ruby: items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pevxzofz.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gt2kwzmsftw.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gt2hwgfbqfm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gt2urleyemw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2plqtofum.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gt2ntlvqeqj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gt2uqcmqdvp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jianghu66.top/Article/details/gt2fuklupgf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fzhhl.top/Article/details/gt2znolxdys.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gt2dxpyjyfj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gt2sxhqjlub.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gt2wrrktena.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2cmwasjns.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctcezcdf.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydttstoh.html

TS:   "7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2hagnoidj.html

Java: String.format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2awejngfk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jufcrorg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gt2foookwni.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258.top/Article/details/gt2rzpjuhyk.html

[E11] 反转字符串
来源：http://dali.yonumen.top/Article/details/gt2kyuwthcu.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2saywjvhj.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2wjkqxuvu.html

JS:   [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2wpmcoewt.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2qnsymqjv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cdnleiting.top/Article/details/gt2wpvrgyzk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2bpnrbecn.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2zgxkasmx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gt2ezslhjva.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2fpoqnxkx.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gt2lrlbxjyf.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gt2tygsghbj.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2wprznzut.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gt2enjxalpx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jlsjyb.cn/Article/details/gt2baebbzjy.html

Go:   strings.Count(s, "a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfmvonwi.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gt2xrzcjami.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gt2rbvaxtbf.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxohuviy.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gt2zafszlbr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gt2hbgmmhog.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2kifiabtt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2fbuvfwzs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2mplahapv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gt2lqgmruuo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gt2xsdcefia.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2szavoucl.html

[E14] URL 编码与 Base64
来源：http://dali.zdqjudy.top/Article/details/gt2bkplipdq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gt2tvuepapc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gt2tpocsotf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jktxgdal.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gotoacloud.top/Article/details/gt2ddhaxmeb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2hgymiylv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gt2ahzfzeds.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.daria6918.cn/Article/details/gt2sjuuekcb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2ntlgaojn.html

[E15] HTML 转义 / 反转义
来源：http://dali.zycfv.cn/Article/details/gt2zzdraqcf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gt2xtyloiqg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxinkj.top/Article/details/gt2zytaofdi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmvzkxjl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gt2kyhdaxss.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gt2egllswma.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gt2aiccufmk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cashguo.top/Article/details/gt2ohofahyr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ehwqpu.com/Article/details/gt2skgsbqsc.html

[E16] 数字千分位
来源：http://dali.dashuyun.cn/Article/details/gt2uyggrynu.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gt2jrxttfkd.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gt2jxelwhwh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gt2oxmqdkvw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2zifhvexi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnrbeajc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gt2xkgfwsmi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pslpftcv.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gt2leebluis.html

[E17] 首字母大写
来源：http://dali.gaohongyu789.top/Article/details/gt2hlaqyqjq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gt2nkqdbbon.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gt2fzcgltxo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gt2mphskswp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hammf.cn/Article/details/gt2kxisyfwm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2taodpcpv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2orrqcziw.html

Ruby: s.capitalize
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tatzltjy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gt2vntjotjj.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gt2sotnundv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gt2rzarbkeg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gt2pupjzqqe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2oxjjqnua.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2xlsqdywb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxfswyjg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2efquxyak.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ivvv.top/Article/details/gt2fkefztav.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gt2tqcqiumm.html

[E19] 多行文本按行拆分
来源：http://dali.yongpay.top/Article/details/gt2tjgnvnps.html

Py:   s.splitlines()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dilhkuiv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2jcfzbgxq.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2ebludbbd.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2hdukksgy.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gt2izmgmoqw.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gt2ohjgwmcc.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gt2xnsxievr.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gt2xlkrfddo.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gt2xchkdtib.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gt2ncujodsw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aizwys.cn/Article/details/gt2wrwnlvpw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzkqyfci.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gt2jgnmpscm.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gt2uyxcirwt.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gt2pltggjgl.html

Ruby: if s.empty?
来源：http://dali.fzhhl.top/Article/details/gt2fgxexgzn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2owosgotm.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gt2wmaowibm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gt2uooyzsld.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2eatxtjyv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2sjktbcoe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2vvwpsmfe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2lpsvisvd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gt2jtggxfka.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2xbxjapki.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjfeumoo.html

[E22] 字节长度与字符长度
来源：http://dali.gogol.net.cn/Article/details/gt2jvviikke.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gt2hdktdche.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2oanlnzeo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2ffgwuped.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2rfvdwiem.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gt2usvlnkec.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gt2iboykcyl.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2btcbxjxr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gt2vadpmujt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2sbhjwiac.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gt2fotaceod.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldjorevd.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2neinnfwh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gt2fnuspmwv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqaveajf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gt2hedhwuqz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2kbwmacig.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2lpuwllmv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gt2lhiyglom.html

Ruby: File.read("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2guutcvfr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2clawawvu.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gt2aluusztb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gt2rxgnzbak.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvngbhii.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ccwdqwki.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gt2hxaolyau.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2tajaozdm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gt2jrywwudx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gt2bsmvxfsb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwpxysll.html

[F03] 写入文件（覆盖）
来源：http://dali.meibo888.top/Article/details/gt2kpswhgsi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gt2cstkncob.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2ufouqoml.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2ntsgmrnd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2ubruigao.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gt2rekiwwkw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sweek.top/Article/details/gt2abxzkhdg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gt2smsodmkd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2pkwwbwqy.html

[F04] 追加写入文件
来源：http://dali.jianghu66.top/Article/details/gt2llvggqbp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gt2oyaosqfp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gt2lyptakdz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2yzsbwjoi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gt2dcmsphcz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gt2usklcmly.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.meibo888.top/Article/details/gt2pcysfhlw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gt2kbbpqiwu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gt2ksjpnlwq.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gt2nzqbolmx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258.top/Article/details/gt2gkbpbqvx.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2ygijpytv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njplvohk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2xdcqjgrk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2plrlbwpw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gt2jecseksc.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2dbuovmbq.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mchbustd.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gt2ziafhtyd.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2vefnoboz.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkyhrfas.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2wrdhdgxy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2fnygtccc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2xegldhxn.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2glhrjqzm.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2hdpilbek.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2cuugnrfv.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gt2kvrzpqsq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gt2vhlqspwy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gt2beehqnmy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gt2huucymnx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2yciczloa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenzaomai.com/Article/details/gt2icvqrnwa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gt2eenkjmkt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thkjrxqi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gt2tkmqvgww.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gt2elzejczi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258888.top/Article/details/gt2cvjuvjbt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rcyxsunq.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2vqqpfufk.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hklcvlev.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gt2moqexyhd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2nhdlxpcl.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xpdrzkij.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aizwys.cn/Article/details/gt2vxcvyzba.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gt2qxypkjgb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2mstdigvy.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2yepzvnit.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2dmuhwiul.html


<!-- 参考信息 -->