代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.yueranfly.top/Article/details/gtqrtpdxah.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gtjjurojeu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtfvfihern.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtpwtrvpjt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtchainggs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtenajnmwu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gtpbswyblk.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtgmuvewbv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gtqohyelcl.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtnxgmngeg.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gtfnpnixcx.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtvwklktjd.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbfzadsk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtkdayvoyw.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gtmvhwbiwp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gtobenswhi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gtkhujcgxo.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwoyhmkn.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtstivbhpx.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gtrhywzeik.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gtghaoxhao.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejhegosc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutuacxxm.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrckxtio.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zdqjudy.top/Article/details/gtvrgommdw.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgiskqkpq.html

Ruby: nested.flatten
来源：http://dali.c1oappe.top/Article/details/gtlgvhsypb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtaypckibb.html

[D19] 按字段分组
来源：http://dali.fzhhl.top/Article/details/gtqvoteasi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtteinvgoj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jyoumei.cn/Article/details/gtwuhoksxm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtjwpjcmgg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtvlercjhe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gtogxeohnh.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gtsuyjohda.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtafqmcsce.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gzhubu.top/Article/details/gtxrnuwjbd.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtrrltjoog.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtxckzggon.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtbsmlxnmy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtkvztwusd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtjpcqakfn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gtkharfcxs.html

Go:   // 手写 map[T]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtloztfydf.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gtluhtvazf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtgcezpawc.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gtfcpdzwsu.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gtbsyvdtap.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gteazyivsr.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtrqsuqgkf.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtrerlaxwc.html

Java: list.contains(x)
来源：http://dali.nwbrower.top/Article/details/gtgqfeokkl.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkgjupfcr.html

Ruby: arr.include?(x)
来源：http://dali.xziqi.cn/Article/details/gtfqtpynpb.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzpsaymrb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtghbnvlca.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gthjcakhho.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gtyvgneojl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gtzsmtaiqn.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gtwqcqgisj.html

Java: new ArrayList<>(list);
来源：http://dali.cdnleiting.top/Article/details/gtniflrwwa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gtgglilqgb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shangyingyoupin.top/Article/details/gtcoebsllg.html

C#:   new List<int>(list);
来源：http://dali.jianghu66.top/Article/details/gtnizmgtno.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gttmobdrxm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gtkyscmzuf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gtquzgtliv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqetqkpw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtygjjfzxw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gtujatyykh.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyjyczvl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gttnfoolif.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yanxiufei.cn/Article/details/gtzlntwzyh.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gthyfbkjgs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetijaknq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gtufqigqov.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gtkqtjykuz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtvgokievc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gtyxcetulv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jiagoushi.top/Article/details/gtxtogecag.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gtyyrtrdbb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gtywnxtobk.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gtoubfbdsk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gtwvbbjwnd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gzhubu.top/Article/details/gtoyzcxbxm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gtvvnoyjxy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpgyhzxo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfhujvpmj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gttomykacl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtiiehubun.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtokbhndmu.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gtxypcwcgo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gtrzzziavm.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtigqkcubd.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtqcgvgzpr.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtkzztzckg.html

Java: String.join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtmrmklnpn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapntsthp.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtkamkbavw.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtbmdurvpb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwzzxnfno.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gtbmagisww.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrvbdufmr.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtjadkbpuj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcumkyzs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtdfaxeiwl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtmzslgivw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtgqotqlik.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gtafxsgsko.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gtuhqklyko.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gtaerqdtwq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtawcqnoep.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gtunwozmzu.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtchyhusfn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gtwqbexvsx.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtmetynuxd.html

TS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtpwhwqizy.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtfulayoic.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejvqgkqo.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtmtjoimah.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtumgdpvxq.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtiasmssud.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gtkrlaxqiq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtsfnxqeba.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtgklabaow.html

TS:   s.slice(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhznoike.html

Java: s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gteexvfmnk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.c1oappe.top/Article/details/gtwhwcopuh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.smart0.xyz/Article/details/gtavufthgn.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gtqddhvgsh.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gtqhouaoju.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gtfbytjzlh.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gtvmixofok.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gotoacloud.top/Article/details/gtypafpnnl.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtooxdlqvr.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtvuqxjkat.html

Go:   strings.Index(s, "x")
来源：http://dali.kuanghao11.cn/Article/details/gtrombetkz.html

Ruby: s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtsohttgva.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gthqakxixy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gtamqmbvsp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gtcbvbkaow.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sweek.top/Article/details/gteexrqyaj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtrlxikpeb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gtarpzhmee.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hammf.cn/Article/details/gtwktnfcsp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gtxigatrff.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fzhhl.top/Article/details/gtshgoxyna.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtfbfpnnmk.html

[E06] 替换子串
来源：http://dali.bjfxy.top/Article/details/gtgyjqpwvt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtnpqeqltw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yueranfly.top/Article/details/gtptpjcvrc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtvpkqrfvq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtpmjhjnbw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtftkmuowt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtgoksezhc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtopywdiwc.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gtcpnojyeq.html

[E07] 按分隔符拆分
来源：http://dali.zhixingplan.top/Article/details/gtzwozljac.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtcwqgbxgt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gtnxxknghu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtwtoldoaa.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsujzivsy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gtmzvamwfi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwffizpt.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gtoiwbvjld.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gtivomdlth.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gtvtcwzvab.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtukrwpdlr.html

PHP:  implode(",", $items);
来源：http://dali.shuidangran.top/Article/details/gtrkxzzsvz.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtzqhvxlyd.html

TS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtncrxolum.html

Java: String.join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gtjvdoftim.html

Go:   strings.Join(items, ",")
来源：http://dali.hongshengwenyu.top/Article/details/gtpfslexvi.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gthjcwmirz.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsggmcotv.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gthkecshsp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxiyitbr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gtehutdldu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtgsclswrb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtssgrufzk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtlpczdhpr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gtcgcbgrte.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gtsuanorzu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtlfqvwsen.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jqgfzy.top/Article/details/gtqokdggmt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtoxtbhtng.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gtbggludjz.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtpdkhgkkk.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtjgkwbxkb.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwuoxadi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuefkoegf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gteuuuhlxb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gtiiehjdme.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gtumiurugz.html

Py:   s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtoyawjxre.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtmepfghnb.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtnqlhhgpe.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtemssxphi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtqyxqncty.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtflevicvc.html

Ruby: s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkhgsaon.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gteacshqej.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gtvqssqsgw.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtpcrvqzsp.html

PHP:  substr_count($s, "a");
来源：http://dali.yangfankeji.com/Article/details/gtavnapihm.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtrvtevess.html

TS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtpuntsdwi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqhdojgb.html

Go:   strings.Count(s, "a")
来源：http://dali.yongpay.top/Article/details/gtixjwantb.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfibsfgk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guannengcc.top/Article/details/gtythjfbib.html

[E13] 逐字符遍历
来源：http://dali.fzhhl.top/Article/details/gtesszyqvn.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtunhkjwro.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangdashe.top/Article/details/gthqmddghq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtbugxddys.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtkgbzmgdd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxdcuzszf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gtnwdlmunp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cdnleiting.top/Article/details/gtarkhnwew.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtwjdoafvk.html

[E14] URL 编码与 Base64
来源：http://dali.pycfn.com/Article/details/gtvpuovtjr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xziqi.cn/Article/details/gtdzbgauin.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gtuxxrqqvh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gtljdanhnw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gtdpvpefcb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtzmubktrg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtooaafbjx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gtgpcvcdni.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtzufpwzrp.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gtwazumtjf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gtetchzydk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.dianchejie.cn/Article/details/gtzkrssqsu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gttntimsud.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtwovckxgh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gtoiryycjp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtimhgjxat.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtibtogqms.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gtymxxacap.html

[E16] 数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtsuceltlj.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtizebhanq.html

PHP:  number_format(1234567);
来源：http://dali.vqdsnc.cn/Article/details/gtnffueens.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtbxhkmiro.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtdjjwenmz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guannengcc.top/Article/details/gtxlyrlxcz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gtffairnpv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtiwlxhplm.html

C#:   1234567.ToString("N0")
来源：http://dali.jiagoushi.top/Article/details/gtorqdkjpz.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtsgqpoykn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gtegxioeyj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gthbqtfhqu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtxefmnwsn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtmqgfhunn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gtiauuyxzs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gtpfqvwysv.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtiaqabchn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gtobpnrckn.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gtyzxsrwkf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gtjrugztsb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yongpay.top/Article/details/gtjegcqnml.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtazyzoazx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gttcymncdh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gthmvwcvyn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtmlbfseer.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gteuwobqki.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gtvnfdamkr.html

[E19] 多行文本按行拆分
来源：http://dali.nwbrower.top/Article/details/gtqtprmwju.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gtwpedbvea.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtkfbecvjw.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtdrgdegdk.html

TS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtylomuvjt.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtoxtppbkt.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gtpjrmiogn.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtkuougqgi.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gtqlhlgtww.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gtrbagxlhe.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gtkhozpitp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtjuhbxcrw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gtcswpjunj.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gtciftgtyl.html

Java: if (s.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtbocbgyly.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gteoujlnku.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtpyhasvlc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gtiozyyxjh.html

[E21] 超长截断加省略号
来源：http://dali.cqqwz.cn/Article/details/gtneefpbti.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gtpqnojccx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gttypqhtkd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtsqudfbjz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtavnduizo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtgcbjliop.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtwdrrxjzj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtkdjsmufw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtxlzqnwyb.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtjlmgafaz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gtpyhehgon.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtpkpjbmqf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtzhpnovpb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gttvpxuuhb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.haohaochexian.top/Article/details/gttktwuhux.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gtyonvfawx.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gtfbnyymze.html


<!-- 参考信息 -->