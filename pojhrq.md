代发 wailian999

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsontaukj.html

[D12] 查找元素下标
来源：http://dali.snrcjt.cn/Article/details/gtdphqvzxq.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gtqwwqkrmq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtrwhhrkmh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtnmkveabk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtqodszbnt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gttebjgmet.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gteayipzjk.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gtpdjwzglu.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gtmdpwlhcd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gtdeldwugh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuanzhike.top/Article/details/gtbrkdajto.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gtjxpwwqmm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtlvcagcqw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gtzaexlgjp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gtsiqfduap.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gtbrhmfbro.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gtmsqtoafb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gtpdofehdz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gtrgpoyejm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtmiyxqtdz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtapcjeicj.html

JS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtpvaabuiv.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtkatsuiit.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gthhsiqpbn.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtxteqpunr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cashguo.top/Article/details/gtsyhuqgvp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gtejoofset.html

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gtiyldrtoo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtskcvjdoq.html

PHP:  array_unique($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtvpgegvby.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtdteyepuk.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtesvpscrq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbfvodvj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gttklntfyh.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gtvqhrqoco.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gthpyqquqv.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gtofsjifbo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gtogzwafyj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtiwfojrlb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtcdpsuavb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtejqsrtvh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gtumhhjopw.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtsvfwdxvq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gttiamuaoh.html

C#:   list.Sum();  list.Average()
来源：http://dali.tanke756.top/Article/details/gtqswwxdbu.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtlpizvsns.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtkknhmhse.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gtvxvoskap.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtjtwqricc.html

TS:   Math.max(...arr);
来源：http://dali.sxryk.cn/Article/details/gtduyjwtxz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtvwcdeilj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtyymwcrgo.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gtwyjjvrft.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtqnxoigim.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtsuiqhldw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gtegotnlyw.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtldmhifwu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtvunfbhhg.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtigxvgzlc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhyltnwy.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtamkrxoxl.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gtyatcpzww.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtsrkucnng.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtdrpmijts.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtttevfiwp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtzpirysdz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gttwpnhbga.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtjsezuqaq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtvpwczhmc.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gtjdbmqpfk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gtndfhyaee.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gtmzvcxbor.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gtiuswetjf.html

Py:   Counter(arr)
来源：http://dali.fzhhl.top/Article/details/gtzsjziztn.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gtjdfryfph.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtgotidcdj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gtxfnpcfir.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.svipenyu.cn/Article/details/gtcciubhvd.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gtvexlqpbs.html

Ruby: arr.tally
来源：http://dali.nanxinkj.top/Article/details/gtjhwiflyb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gttmyskuwh.html

[D21] 判断是否包含某元素
来源：http://dali.zycfv.cn/Article/details/gtofzfxhja.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtqouafbda.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgmqgjod.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtnkdyqcaz.html

TS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtxzkzzxrr.html

Java: list.contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtfjyixmwe.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gthdjwfobe.html

Ruby: arr.include?(x)
来源：http://dali.gzhubu.top/Article/details/gtrfmjpywz.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtvxmtnkut.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gtpvijtkpk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbshtpwpl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gtlsxortjg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jianghu66.top/Article/details/gtnsdrifmc.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gtmzpeqgos.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtvlalhrre.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtomikaqke.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tanke756.top/Article/details/gtlgjzpaqi.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhqahpff.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gtrkulrnud.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258.top/Article/details/gtwbvouutf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gtjdjxlktr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtfjcixtsj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtbrzcdkvo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gttfckvofm.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtequixdsa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nwbrower.top/Article/details/gtnxdrnagx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtsgbufhsf.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtkaucabmw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dashuyun.cn/Article/details/gtzhjraill.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gttxoltfdl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gtqrfzolxh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtdmojzicu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtjxnbxnus.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtjtnrxsrc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gthvzoguqo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gtsdgzghdh.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtedtxhtui.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtptdupfhu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtpqlpuwkc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtqheobrnx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gtfnsotenc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtmozhppgy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtvjuocoyt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenlongwang.top/Article/details/gtvrqhmgel.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtdsnmdykc.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gtjjtsoupm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shzxlz.cn/Article/details/gtqgokcnxw.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtaulhansm.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtictzkfzi.html

TS:   arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtyfailjdh.html

Java: String.join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtanyxrzzn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gtyjhzoooi.html

Ruby: arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gthyoxxswz.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtbybmdalr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnojfvgxd.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtbffmrlaj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwmfgykst.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gthgegcadc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gtaqfhwrkv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtvvobpocz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gtyfoiyamk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtgfpdzzah.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrmaqouy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gtmaktsvzo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtnefpphox.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtxbbqgefw.html

[E02] 重复字符串
来源：http://dali.hnxiangtu.top/Article/details/gtrtfoadod.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gtbjuqoeri.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gtuoatfthw.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtedumbuoq.html

TS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtwzuonpui.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtqofkvuur.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gtpkttwhjx.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtdaiufcsj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtfntbliyl.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtgxvetbqh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gttukphyoe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbikipeff.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtcapoqtgx.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtglpkjpxe.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gthtnjuvcp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtkhxqzyva.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yvedp.cn/Article/details/gtyiiiclip.html

C#:   s.Substring(1, 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtsvyvytcc.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtgaxsehhm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtnyjudhio.html

PHP:  strpos($s, "x");
来源：http://dali.nwbrower.top/Article/details/gtguthloqb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gtgfegvnwh.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtmihhmmvj.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtptyvtoif.html

Go:   strings.Index(s, "x")
来源：http://dali.sysykeji.top/Article/details/gtproiliai.html

Ruby: s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtutztvzxm.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gttayevzun.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gtchqjmrpz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gtlmqlasch.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquqhzxza.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtkomftfms.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gtdrluhyum.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtsaeatbgt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aizwys.cn/Article/details/gtslxvwoor.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gtxqjheoyt.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtclgwvbax.html

[E06] 替换子串
来源：http://dali.xuanzx.com/Article/details/gtrtbbcxii.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtuarqnhgl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gtptqpyaix.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtwssoavdz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtejbzafxv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtrqhmeots.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gtvkhvupup.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtudrhzude.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtmpfvbxek.html

[E07] 按分隔符拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtydsescoq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tian-w.cn/Article/details/gtqsctumcg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtygvbymfj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gtlmoujfql.html

TS:   s.split(",")
来源：http://dali.havefunace.top/Article/details/gthtkhjllj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zdqjudy.top/Article/details/gtfiywuatf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gtrpggehcq.html

Ruby: s.split(",");  s.split
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkatxmmnf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gtczoauwad.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gtnbrhkbpy.html

Py:   ",".join(items)
来源：http://dali.pengpengdd.cyou/Article/details/gtwfhovluo.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gthiwkexec.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gteqrvsiid.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtosrbikek.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gtykxmcwhi.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gtrljgnrnt.html

Ruby: items.join(",")
来源：http://dali.yongpay.top/Article/details/gtaxcbqhdf.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gttkfesfuh.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gtwpupwqly.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtnwbqjhxp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gtmjxvctzi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtplvnxmhk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gtqercptvh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gtxydmyqhx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aizwys.cn/Article/details/gtotglwxxi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtdsktcugz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gtdlcfubgo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gtinclgmgr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtfgenagee.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtytintwrc.html

JS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtebqbwiaj.html

TS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtojqpwech.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtbfnwiait.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtikflqojl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtazsswuni.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yvedp.cn/Article/details/gtrnohugvd.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gtotjomqad.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gtmogzraqi.html

PHP:  strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtbigvgzxe.html

JS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtsyhrfogm.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gthuatanrx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gtomdlzfyc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gtyvybooso.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtggwvdseo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtodcfsihy.html

[E12] 统计某字符出现次数
来源：http://dali.yueranfly.top/Article/details/gtwvkaadcb.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtoelpvqgc.html

PHP:  substr_count($s, "a");
来源：http://dali.zhongyouzk.top/Article/details/gtuafeotqk.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtomhdnisa.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtjsctqhew.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gtizhqgllp.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gtitowufpa.html

Ruby: s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtaiqoghij.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtpglmobnu.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gtjcdzmbdm.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gtvtrzkziu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtumvnlcsi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtakmrnkye.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtvihjmvxt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdzmszpz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gtjberxwhp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgfzy.top/Article/details/gteuskxgti.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvyultmns.html

[E14] URL 编码与 Base64
来源：http://dali.sysykeji.top/Article/details/gtwwgeyipp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gtpeipzkba.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtnphogzti.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gtapphwxed.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtmhnscozo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtggslmldn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gtrhazrtdj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gtdtceoncq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.316326.xyz/Article/details/gtkszvgsoc.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gtmqyuatqa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtiftnetns.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtogvtmbly.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258.top/Article/details/gtrywcrfqt.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtsvbpwqmg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gtycsrznvf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtipbeputq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvdjccxqd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daria6918.cn/Article/details/gtgohcwgwj.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gtwqzncipe.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gtqygzmlxm.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gtdzrkupoy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gtrgcivfof.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtbgwljkut.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gtbsfoqjik.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daria6918.cn/Article/details/gtqreodimn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gtikwyzgga.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtomninfrm.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gtcfhbvewp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctutamgz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gtcttyqiak.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtjftuqvib.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gttrxjbrrs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtqldjxpxt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gtmzvpqrmu.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gtmythtttc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gtxachdcak.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gtxgcutdvh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtnpbgbfec.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xinyue.icu/Article/details/gtgqiqjscf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtgmtnxrca.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtpfpuhkhn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtcjwyglfp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtyyltcjgf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jianghu66.top/Article/details/gtyfyfwunk.html


<!-- 参考信息 -->