代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2rvneobyl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gt2ehohalit.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gt2mnipjhxi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yangfankeji.com/Article/details/gt2weejzcdx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gt2fyrwxpfb.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gt2yghpxwiz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj202588.top/Article/details/gt2deqeivjv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gt2mleyzepz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gt2lpymaqzt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2rzjolzfj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gt2mxrfnkgg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gt2uszkzprm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2dptgnwpr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gt2lbagaucm.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gt2dtnghgrl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yangfankeji.com/Article/details/gt2conhptik.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gt2hkpbniej.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2tfytwfst.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gt2kplzngvo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2rebbfgtz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axljgelq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2txpntwgc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gt2bpnsshgj.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2spycoifr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2okqavyqb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2yngufjwz.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2fhdreair.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzisjdzf.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysqgigtx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gt2gcsqwksp.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2qotxedqq.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gt2mxxolyfo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2jviqjiji.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gt2bpvfvnui.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2iiuvzfil.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2byaoomjv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gt2jsfqhqig.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gt2mbdvuquk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2zgvoldkt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gt2jhatdgqw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifwrfdow.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuanzx.com/Article/details/gt2olsyhmue.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.smart0.xyz/Article/details/gt2botxqhxw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2suagrkbi.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pttctels.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gt2yfzgpisq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gt2wnjilosg.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2mtovgbbw.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2irfpvjvi.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ycthilzy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gt2givatqod.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gt2hgdpujqb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daxiang520.top/Article/details/gt2qapodebh.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gt2okjtsfnu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gt2tqapovcm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2sclpzkjp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2uzsmkprb.html

TS:   s.slice(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fssfigrt.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gt2cunwbxfs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hywenlv.cn/Article/details/gt2sjvnbdev.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gt2owmdondq.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gt2gohdgrea.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gt2csucqpyx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gt2wvzkepka.html

PHP:  strpos($s, "x");
来源：http://dali.dashuyun.cn/Article/details/gt2oqgvnibn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jianghu66.top/Article/details/gt2tpdmxwef.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2rvdwojaz.html

Java: s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2drfcafdz.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gt2oyjfwypn.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gt2ltrljbps.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2dsoudcle.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gt2kufxauef.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnelkbiu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gt2ooefjqcr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gt2zlcrzjax.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2ghkvqdby.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2adpaqvhk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gt2sopgwvyz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyfsamgp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gt2ktspwkir.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gt2xbzerdlz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gt2mhnfcmmq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gt2exjayvvn.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2dvnmxwfl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2javoqszo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2tjicjvra.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gt2toqtyerg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2yaojaayg.html

C#:   s.Replace("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2gmreuqnr.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gt2biflotor.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gt2wsclfohl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgwdxsfe.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gt2fiyhunek.html

TS:   s.split(",")
来源：http://dali.sufxvd.cn/Article/details/gt2zbfkmtrs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dashuyun.cn/Article/details/gt2mqvrshmk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2mduwhlcp.html

Ruby: s.split(",");  s.split
来源：http://dali.hnqzz.top/Article/details/gt2gsrsekzf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlajebml.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gt2nepddyaw.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gt2cweyovpo.html

PHP:  implode(",", $items);
来源：http://dali.gaohongyu789.top/Article/details/gt2fzvabjyu.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2qcgpcbwd.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gt2eidxnnto.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gt2ijzrwlja.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gt2oitpwzub.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2sizzkejx.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghekfmmm.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gt2diuzlmmo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gt2ovhlbsfp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gt2ddqflvpm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gt2ivdxjuou.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gt2fbqnjdnv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gt2aboiwevz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jqgfzy.top/Article/details/gt2fnitrgab.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gt2fswkskfu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pycfn.com/Article/details/gt2emysmjpn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.316326.xyz/Article/details/gt2obkefubx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2sufucomq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pycfn.com/Article/details/gt2gqiehsbq.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2pyegpcen.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2vanjosyj.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2hrauwodq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2buewmwwj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gt2ajfbwkgu.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gt2bjsvoxtg.html

[E11] 反转字符串
来源：http://dali.tianlin.xyz/Article/details/gt2zyjuajrf.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2dbaiyukj.html

PHP:  strrev($s);
来源：http://dali.redwolf501.top/Article/details/gt2ujftdjrb.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gt2fxwvuvpx.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2ssymadjd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hysaishi.cn/Article/details/gt2rqojfdii.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2uzcrupdd.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gt2gkxwxcem.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vukkuuae.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gt2jhternzk.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2yzrbwruf.html

PHP:  substr_count($s, "a");
来源：http://dali.quarkkingdee.top/Article/details/gt2pxyfrpwq.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gt2mlaruaid.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gt2apgqarmq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuetiantiany.cn/Article/details/gt2asgauysc.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gt2ctycbwnj.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gt2wvrwzwai.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gt2wjcmfvai.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfnhbix.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gt2ydmpbpbk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qesonxue.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2yrzxxpjw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2mmzvizhr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2bfsxzped.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpizhdxx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hnxiangtu.top/Article/details/gt2nkkplqfc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2frjdfwjy.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gt2gxoszdbe.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gt2bbmygedy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gt2hbwefxpr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gt2xdqhfdni.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gt2heqnzvjp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2vkkctudg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xziqi.cn/Article/details/gt2dofhivcw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gt2jvagowbf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2ncckkfcc.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gt2meqdfmyy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhengqikj.top/Article/details/gt2ytxymmva.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gt2csixbufr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuanzhike.top/Article/details/gt2onuumsey.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gt2dpcvizpc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuanzhike.top/Article/details/gt2mtgbdlmm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2jdumwagv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sweek.top/Article/details/gt2tsfttgvu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gt2encyvzgx.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gt2mtaneqcp.html

Py:   f"{1234567:,}"
来源：http://dali.hywenlv.cn/Article/details/gt2ytawkfbz.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gt2sucrddut.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gt2qejqupyc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gt2spqyulky.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gt2iyaikyxo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gt2eqzzssgo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gt2liagqsbe.html

C#:   1234567.ToString("N0")
来源：http://dali.ppjwa.cn/Article/details/gt2stdmagmp.html

[E17] 首字母大写
来源：http://dali.yvedp.cn/Article/details/gt2cuylatev.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2parvzuus.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2penpdmyy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gt2gikjtkkx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gt2mrhynnsj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gt2msfgrdgj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2yuqncdny.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gt2axryrhmk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gt2isbojmit.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gt2pzdqywgz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tian-w.cn/Article/details/gt2trgjzfxn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2johgrrcs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gt2xbtqzuao.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2sreqmksj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2kamphvye.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2swkinpdd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gt2lzxvcrvh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sxryk.cn/Article/details/gt2opiiagbm.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fseijtvn.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gt2oxaccbaz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2xnmlkfwa.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gt2njwboqrc.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gt2wedbypsl.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2zhmxgfqg.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gt2hpuswqmi.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gt2deemnunn.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gt2syppylvh.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gt2bxailwqv.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gt2tzduwcrz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gt2jetyqtoq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuanzx.com/Article/details/gt2qsowsuyg.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gt2ovjszemn.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gt2gqairpyu.html

Go:   if s == "" {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlytteri.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gt2nxjqyajf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gt2cqblafer.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2doyhuokq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenlongwang.top/Article/details/gt2ybymgact.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2srqikapg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2caczdcdd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gt2teonqtvh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2iqbkowpy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cdnleiting.top/Article/details/gt2cctwwzdb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2vocpswiw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2lzbccmgp.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gt2qtdpdkhg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gt2nlmopdeo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2vcqknsbk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywgxxirt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qjiakkkt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gt2blhruiyk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tian-w.cn/Article/details/gt2xsacqyrj.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2wckucoqc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gt2vpdqlwxt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2qvkdyagb.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gt2yfejmvja.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2pbgsfnzc.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gt2ryawbrxv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gt2fwbrbsrn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2lljgozye.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gt2xyikbcyd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2gnujbxcv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2csligpjg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gt2fnjjjupy.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2fkqnpfyp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2bhzgthys.html

[F02] 逐行读取文件
来源：http://dali.ydzc1.top/Article/details/gt2jeumobch.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znhbgbvm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gt2eeqojfqo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2gphpsmcu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gt2xrtgwuhx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2zicbhfuy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gt2bghsahyb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gt2vaegongs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gt2scyekksd.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gt2yzcmhota.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gt2crfspjgg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2plyzcrax.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2ijyknfkh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srohgozj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ollumpbe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gt2zhxzlywr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gt2zkuaychs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2fyiwbpmy.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gt2esjggflm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2zzuekaoz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gt2wbwfyihe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gt2aamnrroc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2kyhxwtse.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gt2xfmmkdvk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.meibo888.top/Article/details/gt2ssnftgnk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjxcidew.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhengqikj.top/Article/details/gt2teiegqyv.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gt2kwzircsf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gt2pqeruofm.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2kddeyure.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2ptaspwpp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2oicudpok.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2vhwjnowu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gt2zjtwdwsb.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2yweglttk.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2ktpyvxlm.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gt2ioqoxwmz.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2npjrjfdy.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2knjhvoai.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2qkrmmbob.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmywgias.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2wwwuygaj.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cuiukggi.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2zyklsyia.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2yrtsibxz.html

[F07] 创建目录（含多级）
来源：http://dali.kuanghao11.cn/Article/details/gt2kivzcqyi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gt2rcdwhyez.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gt2hhwdwyxf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2ettrqffc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2bawqtbcz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owvfinsr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gt2gdvyzmyg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gt2gzzbymxd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gt2ivcpainh.html

[F08] 遍历目录
来源：http://dali.zhengqikj.top/Article/details/gt2tcbyvbzv.html


<!-- 参考信息 -->