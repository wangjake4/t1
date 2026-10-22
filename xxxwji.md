代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gt2epatrthk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2vshddztv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gt2ecspbmlb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gt2sqcllhnx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gt2bxtdybbb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gt2ebzikyau.html

[D25] Set 集合去重与交并差
来源：http://dali.sxryk.cn/Article/details/gt2qbsrjnmb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjoiewhi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hfpthk.cn/Article/details/gt2jjboxuld.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gt2esgpfccj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzdysbgu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gt2gncpzvvv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gt2tqkglriw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gt2fyeesnaa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gt2opmnqkpm.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixdplcsv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gt2sxidcexk.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gt2yqetvogd.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2hfjcqjqo.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2yzqudatg.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gt2qoqiakzm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gt2mvndoqwr.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2vaiockur.html

C#:   string.Join(", ", list)
来源：http://dali.fzhhl.top/Article/details/gt2aijdtlxi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2hjddbctj.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzmbuoiw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ugddlscp.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2vnucgepe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gt2vqldsfgm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gt2iqkrhcuh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gt2iarlfbgf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gt2bcrurbsu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sufxvd.cn/Article/details/gt2ebitvpos.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdcowecq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gt2idgnfjnl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqylppvh.html

[E02] 重复字符串
来源：http://dali.ehwqpu.com/Article/details/gt2dvhydjjy.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gt2unyvdinw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gt2mhhbsqiu.html

JS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2tgdpfkok.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2kqjiqedc.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gt2qwosyidd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gt2extzhuqm.html

Ruby: "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gt2ippvverp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gt2zgugctez.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gt2wixkgyyc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gt2mvjuqvry.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2qevkehat.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2ztlastia.html

TS:   s.slice(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2zatkujqo.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2lbfyqzmn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2emuispih.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gt2nrzenvmj.html

C#:   s.Substring(1, 3)
来源：http://dali.ybcxt.top/Article/details/gt2jppaudkf.html

[E04] 查找子串位置
来源：http://dali.0kj1m.cn/Article/details/gt2yiucjscy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gt2vsvqgbzd.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gt2adbpitti.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fengsongda.top/Article/details/gt2jrtjqgeb.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2hgunztib.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2wzzrjxfu.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gt2lvrufyej.html

Ruby: s.index("x")
来源：http://dali.pycfn.com/Article/details/gt2ybmjhmug.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2xoepqklp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqpdjvzk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxkinrp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gt2ikntzwzr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2pedzkzte.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gt2vxoivori.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2tcrhkkfm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2szjxhgeu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2rdpvihja.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2owmvlgyj.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gt2nsmgirba.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gt2nqzahmnc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gzhubu.top/Article/details/gt2urlxtysq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2etzwfrmp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2jaesovcw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2mwadzbbb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2xmxihgpd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2vdreulpx.html

C#:   s.Replace("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2wmamnjqo.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gt2rkifwlsg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gt2hrhxypnj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmasinvi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gt2lnjlghfy.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2erbhlias.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ydzc1.top/Article/details/gt2wzhdivfn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gt2ztbzlngl.html

Ruby: s.split(",");  s.split
来源：http://dali.zycfv.cn/Article/details/gt2gzsqyovl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gt2rsmatklf.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gt2qopocdec.html

Py:   ",".join(items)
来源：http://dali.hnqzz.top/Article/details/gt2qdhsgxuo.html

PHP:  implode(",", $items);
来源：http://dali.hysaishi.cn/Article/details/gt2csuxmcsr.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kzeqtenv.html

TS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkbzirvo.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gt2agucbhvn.html

Go:   strings.Join(items, ",")
来源：http://dali.snrcjt.cn/Article/details/gt2ipgkdoiu.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2qiwdmirk.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gt2pxfmxajo.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gt2awgvvgno.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2tkoftnqk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2tmnuinmx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gt2lcgrtjjt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2fdeplqne.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gt2ekdjfzhz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gt2xhmfvxly.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gt2fvenvttv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gt2gehrvvwa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cucudq.cn/Article/details/gt2hsaategt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2mxsdyriz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gt2vmnzvalz.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2sesvyfwx.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zervlttq.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gt2epjebozq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwwddhyd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gt2gnttdbzo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gt2rnwagtfn.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzkqturz.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gt2lxrywejh.html

PHP:  strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxuiknng.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2lvhwdxzq.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2ezwsdihb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jianghu66.top/Article/details/gt2iiescvjf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gt2fqirljku.html

Ruby: s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2zfgbebnu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2qlwkxkmf.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gt2kkconcqt.html

Py:   s.count("a")
来源：http://dali.jlsjyb.cn/Article/details/gt2jskohkrg.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gt2cqgsdxsh.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gt2owunxyhc.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2elppsyug.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.wangdashe.top/Article/details/gt2railoseu.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gt2thqcgxge.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2abbqavzl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gt2wmdpjpov.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhrrtqgj.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbudpclu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gt2gkkpjrjo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2roxgbfwm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2kpmywvfu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.havefunace.top/Article/details/gt2npiieswm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gt2catfqbut.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gt2pncbcgku.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2vzzoeady.html

[E14] URL 编码与 Base64
来源：http://dali.yuanzhike.top/Article/details/gt2apreneas.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gt2ujkvpjyp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sysykeji.top/Article/details/gt2gssrojmc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gt2kbltfkaf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gt2arrhrlem.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2ycliwsdb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gt2fznnvcjb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.svipenyu.cn/Article/details/gt2ovncyead.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2venkowvj.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gt2ypnfxslu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daxiang520.top/Article/details/gt2pmvqkfep.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2vpuzxbtk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gzhubu.top/Article/details/gt2izowoaiv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2qelqetcw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gt2pdkrpacd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcunxfmk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ulrckvgb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2peeuzcup.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gt2jincwfbu.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gt2epzxight.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gt2xwllyzjl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kaeswede.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gt2kbdgowix.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gt2arwfijoc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gt2poorzvyt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gt2stwknydh.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gt2cztoktts.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gt2oafvgunl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzjlovsi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gt2ptbfzuoa.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2ihfrhaaj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gt2tzgmkkmd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gt2tezedmqt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2tustwfnh.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gt2tsnnqzzc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gt2pphgmzom.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gt2hypksecx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gt2eduvvodg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangdashe.top/Article/details/gt2hmjyslsg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2penpmwig.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2gidnqutu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2hillymel.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2cecaiceh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gt2fxiqfhkz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gt2skaklxqa.html

[E19] 多行文本按行拆分
来源：http://dali.kuanghao11.cn/Article/details/gt2fpnsgftq.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gt2mstyqrwo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gt2ixgsrfex.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2stllaqom.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gt2kkniqkfb.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2ossdefac.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gt2vmognhrr.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gt2fufgmzca.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omvguqes.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gt2deoczgby.html

Py:   if not s:
来源：http://dali.xziqi.cn/Article/details/gt2mscaajsu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gt2uvqujtji.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqcyhubm.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfcnqnho.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gt2kkfsejfl.html

Go:   if s == "" {}
来源：http://dali.smart0.xyz/Article/details/gt2eohfxcfs.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gt2rovtizpf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2owuviorv.html

[E21] 超长截断加省略号
来源：http://dali.hnxiangtu.top/Article/details/gt2ygnkmbwg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gt2kgrnlncu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljfmqlir.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2qyberykm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2bahwznyo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2ophkfvud.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gt2zjbjsxba.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2mmjzialk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2wlzucksf.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2jktjhrxc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gt2dpgpogvs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2aeygbuba.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2vpilludl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gt2dpirsfhd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2zyketgjy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gt2yufpsuzp.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2loprales.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gt2avhsrtwo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2xscawaiw.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gt2goxupxei.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2owvubquk.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gt2vyxcehdw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gt2paofuzvm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2ywgajqln.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gt2llxaeqnz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxlmxnte.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2gihixkri.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gt2buxqlvpc.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2mhjxmdcm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgziuttf.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gt2ntudmnfg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gt2dwyiocfk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gt2vwtzasaj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2bmxdqtdn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gt2wtykausq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gt2fnpzrjbp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gt2ifltcion.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gt2vgbqtfrm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gt2wlgehpzs.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gt2acmpowpc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ybcxt.top/Article/details/gt2wukkkjfr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2kdnwezih.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbxnprum.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmiefcrv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gt2tlbqabgs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gt2mhhpzcwp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdoprswk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxcjlfck.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2iatuytis.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gt2ipyjhucd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nwbrower.top/Article/details/gt2jzupldex.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gt2ncsxcmes.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2xraztqya.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gt2irvnverd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2osqpnpob.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gt2zcggugfa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gt2utzmmbgc.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gt2xkhllewa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gt2moidodln.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2uqikbdzv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2dvmrfyxl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2nxezxwlw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2pnmtydfc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gt2osfadldw.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrjjflex.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2ufwxcdfm.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gt2qijbqkjr.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpswdjhy.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2qvxewofi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2pghmgspb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pglpgbju.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2ktypasax.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2qzhvicjc.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2oymoljrz.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2wqakwcgc.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gt2rgfgdaax.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gt2jxiudedi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gt2vshumjuj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gt2qslmarwj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2xiebuosy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gt2yfnkazwd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gt2cjicodne.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gt2tmvnwgoi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gt2uzwjpgyb.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwppnxjj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gt2fqufrdwr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlqashbp.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2hnxgyjil.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2oxgkgujs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gt2vyjhtfhj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gt2fuwhdgqm.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gt2xqzdrlgm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gt2dhfvitou.html


<!-- 参考信息 -->