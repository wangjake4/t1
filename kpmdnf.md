代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gticyviomz.html

[D24] 字典 / Map 基本操作
来源：http://dali.birdmap.top/Article/details/gtdvmujgja.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yueranfly.top/Article/details/gtnpwhugju.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxuanxn.top/Article/details/gtfxyrbsnw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtxvyibgft.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtutfxtrnb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gtakzfmrjb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gtuqvloqmn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gtjpthyugg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtgicbhehl.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gtplyfrfub.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtzcdraxpu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtsxruhczq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gttuhbdnpi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtlydzyopq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gtlawdvyqz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gtcycmuuqz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gtwljfvymq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtxpuxewzo.html

[D26] 数组转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtlwmuciiu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gtfurxvccn.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtmqldhrnr.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtbijtgzfc.html

TS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gttkqnxyen.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gthrowmkvm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gtucgfnyhc.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtgaballwa.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtjwnunzuw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtteoqrrxk.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gtdqnphlrf.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzmcykoov.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtrywnjypr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gtjilgtbye.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gtedbdncww.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gthcevdslq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtdszbiljm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yueranfly.top/Article/details/gtspkynwgq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gtilxduuzg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gtifwdnfqw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtuuhdpzxg.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtjwmuvynw.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtzovuomkh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gtfsnpydyg.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtixtcyhcr.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtdrnmahoc.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtoqkzwimj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gthfsnunzw.html

Ruby: "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtwoqaklnb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtenwnlcoo.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtyxayswoi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gtlxgdhtvp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtsptnfvia.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtbwftwjqp.html

TS:   s.slice(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtancwpyrg.html

Java: s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gttzgxbopo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gtuzemcmam.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqjokkct.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gtleniqtqh.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gtqdtirpdw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtqplkofgw.html

PHP:  strpos($s, "x");
来源：http://dali.sxryk.cn/Article/details/gthewdtcrw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gotoacloud.top/Article/details/gtwfgpavqi.html

TS:   s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtjauoucwz.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtwnmmclsa.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gtepowmtwj.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtgstinazw.html

C#:   s.IndexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtxjxvtdhy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yongpay.top/Article/details/gtoofobtkp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cheryme.top/Article/details/gtxdfjckwm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gtjsimpvpu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtohwpvdcn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtdfrdlxsg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtnhyjudmc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gtslkywpfz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gteqzflztg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtitxtliko.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gtbltxuymq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtsunlarmg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gtbnpbhehu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtdourrnnm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtwnpgftwi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtxjpnypvi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtzlqkxrtn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gttlejqutv.html

C#:   s.Replace("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtcvbhhfsp.html

[E07] 按分隔符拆分
来源：http://dali.hammf.cn/Article/details/gtsvisixml.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzxceunh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtvxcmlguu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtrecigkvj.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwbbwrxv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnxiangtu.top/Article/details/gtkpugbzgr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtvteclhxm.html

Ruby: s.split(",");  s.split
来源：http://dali.yuxming.cn/Article/details/gtazksspai.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmegtgcn.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gtjsogwctu.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwckkkxbz.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gtqgzkzths.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtlvlrwjxf.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gteudyecea.html

Java: String.join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtzdemufgs.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtwawjgtxm.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtlrppaorb.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtmgujequr.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gtkrwjgwoz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pycfn.com/Article/details/gtoquvsfue.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtlulemkmh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtihjpenkp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtubupdckh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtqxoldqvy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gtxnijvhde.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gtcdhwyzer.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtrhpiiiah.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gtglalcubk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtkjedfhmr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtibgdxvnn.html

JS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtviijxvgg.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoigglbar.html

Java: String.format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gtlpgkmylx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtwkdxdmsg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtqzwgnbvx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xinyue.icu/Article/details/gtjechczww.html

[E11] 反转字符串
来源：http://dali.cheryme.top/Article/details/gtdkgqlxnn.html

Py:   s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtsbjsfsbn.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtphxipccu.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtisokpxhd.html

TS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtcizmkhhu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtzuosmxry.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtijpzhzgg.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtlpdjxner.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gtyuezprgf.html

[E12] 统计某字符出现次数
来源：http://dali.nwbrower.top/Article/details/gtdgibvuba.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtitzufufy.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gtuoxlxdiu.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtxlfoosob.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtejqxgbth.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnerllszg.html

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gtyrcqedwc.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtvczaskma.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gtaytqtvwr.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gtvkgcdzsa.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gtcyousvir.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gtekfdwzmi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.meibo888.top/Article/details/gtiuhrlykn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtnukqplue.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.fengsongda.top/Article/details/gthleusgmq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gthdtmondd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gtcanhhjxp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtubmotnqh.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gtopviaslh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gtpeywoezr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gtvhnsudmc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteathcmri.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fzhhl.top/Article/details/gtjoefjgeh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtessnmyus.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gtgjyzrhsv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gtluwpxnhx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gtwcjqzucp.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzyhrljr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gtirfdjzna.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtjlugwrzw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gogol.net.cn/Article/details/gtnvnckynh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gteerzmizk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtetzxrjmg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.iojbl.cn/Article/details/gtkztnuhkd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ivvv.top/Article/details/gtgjgvjixn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtnoqqnjuu.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtqsegzwnk.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gtoftuvrvq.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gtxpdmzyju.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtftcryaiw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtuduvoabi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtwvfotlfm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gtnjbnegnz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gtxdaidqml.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gtxyitxwck.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtkptsnomx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtotfgahjr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gtmntibxuq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtrsfdysae.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtvkgaarlj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gtkiyjzqlm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtdngqxnrc.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtthvxwpoq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gtimbodqym.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtizhlorxe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtgbybxdzx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtkbmiwgag.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkafofrxi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtrhoxuvfj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtoyaddqgs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtdwmgimba.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gtvsmnsjzz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtnsabmswl.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gtmhyoxpjp.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gtywhwkouy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtltfovcol.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtglxeqnlz.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtxkqyqfbh.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtrbsczrse.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gtvpibaidw.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtbgatckgv.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gtjhyqgzmw.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gthuxdlutk.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gtqnhkibjb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtgubxqtrq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtqijxmoye.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtcpmrifat.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtemwtdszf.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gtgrwxhimt.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gtfxdzgcdz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtpyhhdcfx.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gteorwhuia.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gteagxvdyr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxgewzxc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtxehlqhgg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtknxtpiqh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtsvurmyfz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gtuggwuiuv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtlgwpuolw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtohgmtyop.html

[E22] 字节长度与字符长度
来源：http://dali.wangdashe.top/Article/details/gtkpseirhg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtdmxaimap.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtwihaepvr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtvdkcijab.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtqorlrdnm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258888.top/Article/details/gtvpjuibxh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtnxoltpqw.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258888.top/Article/details/gtuzrpglhj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfnhpzbb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzlzcwebg.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gtxqkkqmqv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgtibwwdp.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gtvlawifmq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gtnhvecbhz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtmekjltfr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gtarzhmycr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtztakkieg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtldjjujxz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gtsxbbrsom.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtsjhfqfvx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtyntacytg.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gtzffrkpyy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ybcxt.top/Article/details/gtacgovlzz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhixingplan.top/Article/details/gtremgmhon.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtzapmdwav.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gttwhqukxs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtedaqncjy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtgcnedxjf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gtrinmdysa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gtjxoajunr.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtshksxodf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gtensdxdtb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtrpgkpprw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtezcazhvb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtavvnnuzu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtutbrkcwj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gthqhoorgb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gtzzovrgxp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtmanyphby.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gtfbirsumj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gttlpjkntw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gtlmeedzoy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtxseiflsr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtnwlwqmea.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gtgtjdwqbw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtjgfbhixw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jiagoushi.top/Article/details/gtqrenwowz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtofverqfw.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtenivtmgh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtwupvbyom.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtffwodjsk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtzckzmdoz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gttvcmuszs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtqrbdfzjk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.c1oappe.top/Article/details/gtjlidytuy.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gticqvdnmw.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtnvvxpcls.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtguejueol.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtmkkpoqsp.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtwhpwhuyc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtyrwyknmv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtjtowhfuo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtuhblebhq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtkrninfhx.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtuniywupi.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtzzxjomei.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtdhcvpkaw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtsfjeohay.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gtniupfyyy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtryurwzdm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtlpvyzyzg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gtrpbxlukm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtecrmkzxk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcefraet.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtbjmgtxvv.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtjyaoihmv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtwqhysyfi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gtqdkgkrhz.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtlgosbqzy.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtpjkcvdqu.html


<!-- 参考信息 -->