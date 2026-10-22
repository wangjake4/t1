代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.zhongyouzk.top/Article/details/gtkrljsofn.html

JS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtqplcbezy.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtsctmfxql.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtqlirukmd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtpdyqvzsl.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtwrtfmagt.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtryhfhzey.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gtvccvwnyw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gtlpbbhmav.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gtvjuoqvyl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cucudq.cn/Article/details/gtczkqpjft.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gtpowvowaa.html

Java: new ArrayList<>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtpsjpdmsg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtihpnuqvy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gtzyptclci.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gtygvdaxuf.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gtkwabuzay.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtjnhpvmbp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnieucfg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtwoeunzad.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtqggaqflp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gtfmfqpdys.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtlochfpak.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pengpengdd.cyou/Article/details/gtqiadczja.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfjwfvpg.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gtljhynqgg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gtzjqkllkq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gttrmwjxbn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtjuyvilug.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hammf.cn/Article/details/gtkaqypidu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtxousjimb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrspebirf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtgmvbbzmw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gtjpjhodgk.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gtbjaoieub.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258888.top/Article/details/gtojqsgubu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gtqvjcdchk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gtikohvwky.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gtgyabqlup.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtujttvyfd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtkkhjhifu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gtvafxxphq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtekzdpubq.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gtfprpymwi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gaohongyu789.top/Article/details/gttsyjeexs.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtmtfaqslf.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtypmlxzcx.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gthhanvosp.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtepdmzsmk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gtgfcavxam.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gttbsqebvj.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gthtdtfrbj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthffgpltf.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gtdtsbciix.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqugyxlxg.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtywihnzfv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gtcocbjwgs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tanke756.top/Article/details/gtptlpgsdp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtxohdkglv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtlglltwwk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gtszykeltn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtntixwddl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gtffcglysr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtqptonrto.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtwmbdwzca.html

Py:   "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gthwclvqxx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gtgtbloggo.html

JS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtjmcrvbrm.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtlxkbnddl.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtjpipxygd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhongyouzk.top/Article/details/gteewxzzbo.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtpgerusxd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sysykeji.top/Article/details/gtatssqmnv.html

[E03] 截取子串
来源：http://dali.sxryk.cn/Article/details/gthnndigln.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gtmszdrwdc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtwwcmotrp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtyinuhhtw.html

TS:   s.slice(1, 4)
来源：http://dali.shuidangran.top/Article/details/gthudqhwzs.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtzmnracck.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gttxwhgtyt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtgskiwdas.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtxvrzmtfe.html

[E04] 查找子串位置
来源：http://dali.cdnleiting.top/Article/details/gtwxutemgx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtvgweixne.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gtelpuoxal.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gtuzbvxwlc.html

TS:   s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtsmqlyzka.html

Java: s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtdfwpjsbm.html

Go:   strings.Index(s, "x")
来源：http://dali.daxiang520.top/Article/details/gtuzglcssp.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtniforvan.html

C#:   s.IndexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtwsyndfyk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gtobgmjysr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtbsqicuym.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gotoacloud.top/Article/details/gtprlbrxam.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtmvmgcnmn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnghgrncw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtxxewslpl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gtseujbvqd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtiwyonmup.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtwrxypdae.html

[E06] 替换子串
来源：http://dali.yonumen.top/Article/details/gtliproeiq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gteclpegng.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jyoumei.cn/Article/details/gtubiscyiq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gticrhqxac.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtfhqrphyz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtzcjeerrq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtaicmcldc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtndlzefhn.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gtnupcmggw.html

[E07] 按分隔符拆分
来源：http://dali.daxiang520.top/Article/details/gtmuopkxiq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtoxwirrvl.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtmeydmltq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258.top/Article/details/gtxkzpussw.html

TS:   s.split(",")
来源：http://dali.jqgfzy.top/Article/details/gtkcewghse.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuanzhike.top/Article/details/gtirrxpbqb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gtnmlajdcj.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gtrcyjzajm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gtbtxfwjjz.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gtfklompdf.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gtpghsmaia.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gtvamrlkiw.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjjhsito.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtsmyaxmtp.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtticszzix.html

Go:   strings.Join(items, ",")
来源：http://dali.yonumen.top/Article/details/gtkgpcseql.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtmxmktwkf.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtlbtdqwjh.html

[E09] 去除所有空白字符
来源：http://dali.svipenyu.cn/Article/details/gthgxwuamf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gtzyujptgl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gtyjzpogsn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtgfwfzvsp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtfmsepdik.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtebpxwctv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yuxming.cn/Article/details/gtnmmzjail.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gtfddaqgvb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dashuyun.cn/Article/details/gtfkqyehjq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gtpytstogn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoopqjeh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gtrsfwerkw.html

JS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtymvmntpm.html

TS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtkaphtokk.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtkijnkany.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtwwnyctic.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtwthdcnfy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtnfgzyhrv.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbmysxeh.html

Py:   s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtvpikzccm.html

PHP:  strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtzsohiqvk.html

JS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtivlbsqlw.html

TS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtvvhdmfem.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gtmxwiaezb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gtnairjgqo.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtvhjlxlqy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtsrervguw.html

[E12] 统计某字符出现次数
来源：http://dali.hnqzz.top/Article/details/gtvhqzlyww.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtkwuybpru.html

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gtolnnssyy.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtfrpslwvu.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtcrqrprbh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xziqi.cn/Article/details/gtaotaopnl.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtgfhudihj.html

Ruby: s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtsewutomq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gtgcywvbyz.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtmtdqoqrp.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtjchmsndm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gtjvvyifjo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtfmdryabp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtrtupwicu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtghfebruu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shzxlz.cn/Article/details/gtnxnxfara.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtxjjljynw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gtdkpxvqqi.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gtphkqbmno.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangshuangyany.cn/Article/details/gtcvzhdutt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gtddwknqus.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xylfe.cn/Article/details/gtxgeffqup.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gtqddyhggc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yueranfly.top/Article/details/gtfokjaddo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gteybmmbrj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtpvoboxeq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtpbcxhhpn.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtergxfmxh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gtkjswtuxe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtkadpsros.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gtrerhlbvi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.birdmap.top/Article/details/gtcgrtoqni.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gtucjujuvk.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gtuzwoykjl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yongpay.top/Article/details/gtbkiehael.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gtqajucbfx.html

[E16] 数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtjothutps.html

Py:   f"{1234567:,}"
来源：http://dali.cheryme.top/Article/details/gtbkwkydox.html

PHP:  number_format(1234567);
来源：http://dali.kuanghao11.cn/Article/details/gtfpjjjkaa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtclnmjpna.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtzfscnzfj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtokuaxkal.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gtfaqflvpz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gtldlocgxj.html

C#:   1234567.ToString("N0")
来源：http://dali.snrcjt.cn/Article/details/gtvocvqqzg.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzymgqvvc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gtbhdduhkj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tianlin.xyz/Article/details/gtaktmecaz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtrceckaer.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtlbjkuovh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jianghu66.top/Article/details/gtmrottvqr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtmqfstciw.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gtalunyxpd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gtjptfslzb.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtwipwsygv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gtezzurbza.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gtbmqrpsts.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtyfuobefx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtrslnwrlz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtcbpzkknw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtmopzdflj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gtpxkmdvpq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtajzyfpph.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigufen.top/Article/details/gtvbpaldvy.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gtuuyfvauv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtrksswuzl.html

JS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gtdxvmwjip.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtwrsiszye.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznlsfeoc.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtzxbbsstz.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexfooqtf.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gtteytbkqw.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gtvheutgbx.html

Py:   if not s:
来源：http://dali.snrcjt.cn/Article/details/gtpiunsauf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gtxqfgxulr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtxcgkfjfa.html

TS:   if (s === "") {}
来源：http://dali.xziqi.cn/Article/details/gtvqzxhksq.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtbmttaepe.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gtodungddb.html

Ruby: if s.empty?
来源：http://dali.jlsjyb.cn/Article/details/gtnxjlbhtc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gtvwqhudel.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gtemzwmdxx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gtnayacflw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtjmvmyzqs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtijukrjrq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtklexfoem.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtwtgofxcv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gtwqghstpu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtdnlrrhkz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gttqcohrgl.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtefdnfsll.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gtmgwunjyx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtcexxicju.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtunkopxeo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtnojxguxe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yonumen.top/Article/details/gtwqfztihe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gthfbhoxlz.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtijuhtfbi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gttcwjssct.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdfswvbdo.html

F. 文件与目录
来源：http://dali.ivvv.top/Article/details/gtuoqwexol.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfhoxdahk.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtosegqmbf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gtxinsjnpy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtyagqfkwh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gtvdkhpimh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtsjqhjaqb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtbhntmduw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gtkxieyody.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtxjvnaudw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtnnrwdudf.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtfcpbziwq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gtvbgxrnos.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gtctntbeuz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffrqxbll.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtkzqtfndn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtccabdxpn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtwkfpgkyb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gttftrfrqj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xziqi.cn/Article/details/gtehlaetft.html

[F03] 写入文件（覆盖）
来源：http://dali.kuanghao11.cn/Article/details/gtiinwxzef.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gtkixoztdi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gtgdaqiwnw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtebsyimjc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmlnbccb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gtmsivndfy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtbcqvxaua.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtjgmauudi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtoellwssg.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gtkojtjtdv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtpkwhxkbf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gtvforxasm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gteswwqrwm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtmyxyabzw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gtqpmlempg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gtccizicit.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnxiangtu.top/Article/details/gtznhmhves.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtbfqjnkov.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtjqhpxrhn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gthkkztlxp.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtsldmatlw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjgbjhwn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtrfqzaljr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtlmzippxz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yonumen.top/Article/details/gtxkpwroou.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtmtkfbcgt.html


<!-- 参考信息 -->