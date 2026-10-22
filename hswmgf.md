代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdusfckh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcimkivq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gt2tciklpsv.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gt2zpzaaups.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gt2awhjzefh.html

C#:   list.Sum();  list.Average()
来源：http://dali.havefunace.top/Article/details/gt2murtrkro.html

[D17] 最大值与最小值
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrcnztmj.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2jrgphzbi.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gt2keokjpsk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yueranfly.top/Article/details/gt2coqssmzg.html

TS:   Math.max(...arr);
来源：http://dali.0kj1m.cn/Article/details/gt2rfhvquji.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cashguo.top/Article/details/gt2vvvraypq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqelckgt.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gt2kweitpge.html

C#:   list.Max();  list.Min()
来源：http://dali.316326.xyz/Article/details/gt2uuxdynje.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gt2utulnqaj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gt2lfrcqtft.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gt2vhqvjtzh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gotoacloud.top/Article/details/gt2eqcwvsux.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gt2ojxxvnpc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2kjguhrxq.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gt2xlwawkep.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gt2ydsmmned.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2sujvsxuo.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gt2wdpvlzuf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhixingplan.top/Article/details/gt2zrvnvwwx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gt2mzilezex.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gt2ujxkrfwz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gt2imiqzphf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gt2bxrnzeit.html

Go:   // 手写 map[string][]T
来源：http://dali.gotoacloud.top/Article/details/gt2rjopsonz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cashguo.top/Article/details/gt2ytecqkme.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gt2skbhfwzf.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2jtmpzozf.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gt2gvfdmtux.html

PHP:  array_count_values($arr);
来源：http://dali.ydzc1.top/Article/details/gt2dnwomzkv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2xbkbadag.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gt2vlmkckvu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gt2kxqbmbaj.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gt2bheekqpa.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gt2tuktqdgj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gt2gvkslgsx.html

[D21] 判断是否包含某元素
来源：http://dali.316326.xyz/Article/details/gt2kefsqmvb.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gt2ukjlcoqb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.smart0.xyz/Article/details/gt2xopebcqv.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gt2rwmevndm.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gt2zyoczoht.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2efvuxtcv.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2iwpubrna.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gt2ewryrydx.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2zxvsuwxp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gt2rxeciyod.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ikxibltb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvmufpo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gt2xnmzhgaf.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gt2sowkeufg.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lszgjaeg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aibaodan.cn/Article/details/gt2czuekplb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gt2tnqsqems.html

C#:   new List<int>(list);
来源：http://dali.aizwys.cn/Article/details/gt2tbwytqjg.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gt2edplrwee.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2rnavhilu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cashguo.top/Article/details/gt2smnitiop.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2kpmscvau.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2wludjcgt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gt2hllamdby.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apvcwbdq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gt2shvlpcuj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vritcojl.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gt2vrugnifm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gt2jclnxdfx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gt2bhxeeqvt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xylfe.cn/Article/details/gt2azbeyvbc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2jaqvfhkb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2rgkoqhmn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gt2txvvoman.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2efridqsy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gt2umafykwn.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gt2avovtxmi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gt2qerajati.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gt2hhimyiqu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gt2raohojml.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gt2eocftzun.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbfdprns.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gt2cwsdqmyw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gt2ejaeqviv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2luwsdjkk.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2fmwyezhd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gt2xjljspgq.html

PHP:  implode(", ", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvnvirow.html

JS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gt2ndpiikmo.html

TS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2wccnkfun.html

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldtpoglg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gt2zlcwwmra.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2vxnxcnum.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2afviqopn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2sxrjrerz.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gt2doxildyh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2loiuxqvl.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2dejqkkcg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gt2siprozfn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gt2zowetmso.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gt2otvrhnsf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gt2zxtzdgpp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsbtbtvn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yongpay.top/Article/details/gt2pypadrow.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gt2evuivrso.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2hdoqkqug.html

[E02] 重复字符串
来源：http://dali.havefunace.top/Article/details/gt2qvkuhbta.html

Py:   "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2gtbtaljv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gt2uvxccwgv.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2htagnxsg.html

TS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gt2qbouvckt.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2wrfyrfec.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gt2rcywnsts.html

Ruby: "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2axhrxmcz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gt2tbmqqbut.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gt2avomzvlw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gt2yyhicsrh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbtnxexg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gt2gyzunkrh.html

TS:   s.slice(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhutxjsv.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzmihnbp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gt2mykqopei.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.svipenyu.cn/Article/details/gt2eypwhidm.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gt2frajhwoy.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gt2rqewdrqy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2ohiiuhpe.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gt2ugqchhoy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gt2nvoilmqd.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gt2syaqegsd.html

Java: s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gt2tkdqsfay.html

Go:   strings.Index(s, "x")
来源：http://dali.cdnleiting.top/Article/details/gt2gxwwmpcm.html

Ruby: s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdbhrxqp.html

C#:   s.IndexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2bufmoqlu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.redwolf501.top/Article/details/gt2vvfeobfh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhnxmlcd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptlzwhme.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2bmbaunru.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gt2mcajabxs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gt2hthlohjm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htjcrgrp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gt2gadrtwgm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2azpugzej.html

[E06] 替换子串
来源：http://dali.ivvv.top/Article/details/gt2xwuvhpgz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2wiwbelua.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gt2zkmoexmk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2ymtkouin.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2cpkzjwnn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2hortkwuk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gt2iklnjpgb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brtyxefu.html

C#:   s.Replace("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2cqkdvtpe.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gt2olcejsws.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gt2umeaymvr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnehsgzu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zdqjudy.top/Article/details/gt2cuorqjgw.html

TS:   s.split(",")
来源：http://dali.yongpay.top/Article/details/gt2vnimidrw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nngalong.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gt2ipuosckn.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gt2bljyfmxy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gt2wmhpakzd.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gt2yzcdegca.html

Py:   ",".join(items)
来源：http://dali.yvedp.cn/Article/details/gt2trszilpf.html

PHP:  implode(",", $items);
来源：http://dali.shzxlz.cn/Article/details/gt2uflpodmd.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2olewbxfl.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2racchvtg.html

Java: String.join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gt2zqcnluhy.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gt2mhrxuoid.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2irkrlfpm.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gt2wchwbtnl.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gt2gdhiwdix.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guannengcc.top/Article/details/gt2tpelvdfy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2ozwfkofu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gt2ldrluzsn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gt2mgmeelha.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gt2upyfnugo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnqzz.top/Article/details/gt2mcewuwnt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gt2cfnwlcat.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gt2tgtnnqpz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gt2catczvtb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mnpzjpyk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gt2umorezdy.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2qhgoqsqx.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2idboxaho.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2wviocfeu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2cbqkskjo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2wqhplali.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gt2gviczufd.html

[E11] 反转字符串
来源：http://dali.meibo888.top/Article/details/gt2cernhjvi.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2xglnvedj.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2tvsbqqub.html

JS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2qultvurk.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gt2eeahtdgi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gt2logcqckf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffhtvbnb.html

Ruby: s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2xibvcldj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gt2umzqmcsp.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gt2qhfwnaiq.html

Py:   s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2uqplcfya.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gt2cdjvaoum.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gt2tzporkxi.html

TS:   s.split("a").length - 1
来源：http://dali.sweek.top/Article/details/gt2vqmdybhd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gt2ozqxqmbt.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfptfoiq.html

Ruby: s.count("a")
来源：http://dali.andypj.xyz/Article/details/gt2itjznidq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hysaishi.cn/Article/details/gt2eabyfnut.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gt2waxjnigv.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gt2hzdqdktu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gt2jsofwkeq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2beawcxkz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2jgbwrsxf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gt2aycyboag.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangdashe.top/Article/details/gt2qhgxorzy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gt2cckpyqin.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2bolbwanj.html

[E14] URL 编码与 Base64
来源：http://dali.pengpengdd.cyou/Article/details/gt2miznzdil.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gt2qgwqwmfd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gt2tlnybjdk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gt2achebedg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gt2polldgsf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.iojbl.cn/Article/details/gt2qrkbkfwh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtsfaoyv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gt2cowkyael.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2knbkqccu.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gt2rwlffvjh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2wnrhhhon.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gt2utmqztbc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gt2rafzhrpp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jyoumei.cn/Article/details/gt2tkcacryp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gt2jtonfrbv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gt2ydyjnhwu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gt2efjyvgkl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxkkpzin.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2ylpxkote.html

Py:   f"{1234567:,}"
来源：http://dali.zhixingplan.top/Article/details/gt2dfnedpse.html

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gt2ugjvmxzh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gt2tstrswoc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gt2esbgmxoi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gt2sonoofdf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdultdw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2kwimhzqn.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gt2hbljzssy.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gt2esgobuxz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ehwqpu.com/Article/details/gt2skubhcdb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gt2ftmyrneb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gt2nzjdlmfd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbgoynft.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gt2pgrhmltp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gt2nghpdvdl.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gt2pxadnuzj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gt2shsybhmo.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opoodnyw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gt2qrtsvsox.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxgosmqo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2tdhksiks.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2akbojqsf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejtejnau.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2wfmcdiiz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gt2apxmtncx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gt2uodknidr.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gt2lourargq.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gt2jfikpzdk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbvcmxsu.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2ffipoxyn.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gt2hkrpkcbj.html

Java: s.lines().toList()
来源：http://dali.yuxming.cn/Article/details/gt2qbuzmkiw.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gt2foguhnkq.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gt2wwhjmvge.html

C#:   s.Split('\n')
来源：http://dali.jinqigfzy.top/Article/details/gt2zssllwvq.html

[E20] 判断字符串是否为空
来源：http://dali.316326.xyz/Article/details/gt2djnsifrt.html

Py:   if not s:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvmhtwau.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gt2lhiltoql.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenzaomai.com/Article/details/gt2fvpmmcte.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjslrnws.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2zpicsgur.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzhlposh.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gt2eatauckq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gt2ngcicuxf.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gt2sgldmfgw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gt2fonmpzhs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2jnemcyje.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2xuftlido.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2xgwfghjj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2iekadnsz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gt2upytykoe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2rzujdksz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvfbbuci.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyhmtsw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gt2qzdcasxt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2kimjarsl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2slvuhouy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gt2vutzklbb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gt2lznoktwh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gt2xjgghttk.html

Ruby: s.bytesize;  s.length
来源：http://dali.guowangkeji.top/Article/details/gt2euiacjru.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gt2omzdjzbf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2fssuryuu.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gt2glshblaf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2rimziomt.html


<!-- 参考信息 -->