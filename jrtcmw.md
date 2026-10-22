代发 wailian999

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2firfertw.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gt2oinzymhe.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2ldgautdd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2ubplpipk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2qneknlws.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gt2vctizzmn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gt2mptjkzmx.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcjkdgtw.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwedfhrd.html

C#:   list.IndexOf(x);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijtowzej.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pigoevcf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gt2ammwkxoi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.havefunace.top/Article/details/gt2hnwvjjpe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2nctdlemx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkdiudsm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2qkbkshdv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gt2uoyqxcxt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gt2sljkymwq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2dmgmxubc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gt2hmjeazxt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2vlavfnah.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2jrgetzxb.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2cnmtwupo.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2hvzxmbqy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sythnymt.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2xhtoqiyh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2orxvavcc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2jjtuyvgj.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nojhlmbq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2stpmiyyl.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2vmuxmfqb.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gt2cpgipymv.html

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gt2jpxmuluy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gt2ksuxemlx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2yxcdhwzf.html

Ruby: arr.uniq
来源：http://dali.sufxvd.cn/Article/details/gt2pfxfvcmt.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gt2xjlrrbjf.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gt2xswzhkov.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gt2zuwyyqgh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gt2hgwxgmql.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2tfzinatu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2brutxgya.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gt2ysdzmyqy.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gt2xocxcwwj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gt2kjscvjup.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gt2tsjityso.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gt2isvffkzz.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gt2jgzqckmo.html

PHP:  max($arr);  min($arr);
来源：http://dali.xinyue.icu/Article/details/gt2pkshlkuo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gt2kqljuqiz.html

TS:   Math.max(...arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2vfwcntcx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2dgjercwq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2cldqtqpl.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wonjjagb.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gt2uobcrgek.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kvujwmmr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gt2pbgpquxm.html

PHP:  array_merge(...$nested);
来源：http://dali.gogol.net.cn/Article/details/gt2osvlyfgc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ptakfcpg.html

TS:   nested.flat();
来源：http://dali.jianghu66.top/Article/details/gt2xslkktpk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tian-w.cn/Article/details/gt2hakaxmee.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gt2lgnhabrd.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gt2ejtqmqda.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2kltsgrpr.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gt2ghptwtez.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gt2iblermeo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gt2kqudrxao.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gt2xnkegvjz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gt2dfzdmzuf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gt2rhqjnmko.html

Go:   // 手写 map[string][]T
来源：http://dali.yuanzhike.top/Article/details/gt2vliodbhg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gt2msxrtupi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenzaomai.com/Article/details/gt2apcmltnb.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2zfbvuzvq.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2gtrlgfom.html

PHP:  array_count_values($arr);
来源：http://dali.yj202588.top/Article/details/gt2gwmvgttw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gt2prvsoinz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2irftqsnb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gt2mzcqdckz.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gt2wmhavxmh.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtqqrtuv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gt2uqnwswrs.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfqejhix.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2otgipnwp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tian-w.cn/Article/details/gt2omhxkfba.html

JS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2iblukwtt.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yazfskgu.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2epyntdhd.html

Go:   slices.Contains(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2xfgihjxj.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gt2cquwvzgp.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gt2snwphzit.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gt2gqsttuhk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2vdtdzihd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gt2yzkmufan.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2fnfoigny.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gt2hwgxhonf.html

Java: new ArrayList<>(list);
来源：http://dali.daria6918.cn/Article/details/gt2dlntclub.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2xqhqpljk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cdnleiting.top/Article/details/gt2yvaajwts.html

C#:   new List<int>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2xsgnlwfp.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gt2lkbhqswu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2mzerpqhw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.andypj.xyz/Article/details/gt2yhweqlsc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gt2hsaoikhy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gt2wwhrxbvl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxinkj.top/Article/details/gt2juphbpnc.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2qbnbyrbu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gt2xtxsfoap.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fzhhl.top/Article/details/gt2xtinlheg.html

[D24] 字典 / Map 基本操作
来源：http://dali.shuidangran.top/Article/details/gt2vcikfgjg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gt2yssknhgs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gt2rrcwuebh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gt2ywzcpvqr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2xlbecvkx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gt2iorbfbbo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gt2gozpamyq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2bqxxtmsb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.vqdsnc.cn/Article/details/gt2rqeqrnzl.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gt2nnnazqil.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gt2zoirgest.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gt2gcdxyqhg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oraxywmy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhengqikj.top/Article/details/gt2cwfwejwk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhpuwtxc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gt2dzllqujt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tanke756.top/Article/details/gt2gfeirufp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xylfe.cn/Article/details/gt2qzhccgwj.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckbaadxu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gt2lkxetckf.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gt2ibbkblyp.html

JS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2acvvchbg.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2rhcrshpb.html

Java: String.join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2hswzursm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gt2nsptsbbo.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gt2jruvmyra.html

C#:   string.Join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gt2zcrgbaql.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2tbagbjng.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gt2tainsawa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2eeqidnhm.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2bfipdhox.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gt2jkplkiwt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejmoerzg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2kcyqoief.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihvghpmp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yangfankeji.com/Article/details/gt2awayvaxp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gt2bxapkhaf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gt2hsnobusw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2qmudgkuh.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gt2eucxwzdi.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2qghfpapv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jianghu66.top/Article/details/gt2wlpedgck.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gt2ffmbgsdb.html

TS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gt2gepofgid.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2vdiytodw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daria6918.cn/Article/details/gt2cuvxqofx.html

Ruby: "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gt2mwvzzdcr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gt2zdkdgxvm.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gt2vwbjusmy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tian-w.cn/Article/details/gt2mgsrhhit.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gt2ylgzznml.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2assbgbwk.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2vsoucmok.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gt2wqyqymlr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gt2qncpvpqi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gt2omqrjtkk.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2hzdakpcn.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gt2rzkkjrtq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gt2jziratno.html

PHP:  strpos($s, "x");
来源：http://dali.zdqjudy.top/Article/details/gt2lphhzkkc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gt2utcqykpb.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2npkizpmb.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gt2sruhgote.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gt2lxugdoff.html

Ruby: s.index("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2fdvrdzdp.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2clbfzpfm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.mhx1999.top/Article/details/gt2iyouurxl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gt2uxxmvtwg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gt2xfkghizq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2ipnfpfqa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gt2xcblbcra.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2olauxvqj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gt2kiwaodym.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gt2djxdqfsy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejfvtmah.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gt2fpkrvnrq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gt2rgkorjvb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvvbwrvi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcmxcdvf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2tzdtkrqv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2byewasvj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2kaurwjek.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2ljavpldu.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2korwapcq.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gt2zkyfifvv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gt2nhkvzdqc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2tlogzfic.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gt2owwostxz.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gt2ustietuh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gt2niynidlx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gt2ifyvqwdx.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gt2ezkhgstf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2xkfkaobk.html

[E08] 数组按分隔符合并
来源：http://dali.snrcjt.cn/Article/details/gt2cxhbkaeq.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gt2mwmxpcdy.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gt2yfiimrzh.html

JS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gt2pipqkqlv.html

TS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2uauabnrs.html

Java: String.join(",", items)
来源：http://dali.c1oappe.top/Article/details/gt2pidvvgks.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aquwbxrv.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2tuxrmsfa.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2tjnagxnu.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gt2amckldup.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gt2mpzmcnrr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2ktlxawmj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gt2jcuxqsur.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gt2wzvgoomd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gt2tzcqbkro.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gt2kvkassdr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tian-w.cn/Article/details/gt2iznqmtse.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntockhyi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gt2iqoiwjld.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2ryppmwuy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gt2xocordop.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2detfabor.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2wngayzsq.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2jdiyicxd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvomtibl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2fmhisgze.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gt2nqepzfhm.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxnzysff.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gt2gosdezfa.html

PHP:  strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2yajvggyo.html

JS:   [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2lqrnqboo.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gt2iyskgvwv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcbvuiap.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gt2irlswekf.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gt2jeyukkqe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2suchwlsy.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gt2lijbpypq.html

Py:   s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2vxadqeav.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gt2mzqinoyz.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gt2sepdvjuf.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2uqixoofb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gt2oeuagpdj.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gt2nufjrrpi.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gt2jbcpmegv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhengqikj.top/Article/details/gt2chndecgg.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpmcjzpf.html

Py:   for ch in s: print(ch)
来源：http://dali.nwbrower.top/Article/details/gt2ocwfzajj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ppjwa.cn/Article/details/gt2xbezllvy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gt2iihdsjrs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2czjmenou.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2rmqxkorr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj202588.top/Article/details/gt2puljdllf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gt2eopzxnpf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gt2hamdmcdt.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gt2lugajojn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.havefunace.top/Article/details/gt2wtvqrzsa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ivvv.top/Article/details/gt2gdesfoix.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gt2dautqhrc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gt2zrkpxhhw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2acavdpai.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gt2fwaylefc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gt2mjmhqdam.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2aevhalnz.html

[E15] HTML 转义 / 反转义
来源：http://dali.dashuyun.cn/Article/details/gt2ldvnghyg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gt2vpdnpttl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sysykeji.top/Article/details/gt2dxuygxnp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gt2nfmtkhaq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gt2agrxltif.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbivxuid.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258888.top/Article/details/gt2dinlrpfb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gt2sfnnofng.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gt2jdsgvbrl.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gt2dlrteqdz.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gt2ucppwbwc.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gt2yuvecsek.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gt2fapipbga.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gt2kkomlfbn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sydmpuos.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwaeaiwf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffjkyyzz.html

C#:   1234567.ToString("N0")
来源：http://dali.ppjwa.cn/Article/details/gt2boajtidp.html

[E17] 首字母大写
来源：http://dali.fzhhl.top/Article/details/gt2ibrpvjqr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gt2epcwxsyk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.9152youxi.cn/Article/details/gt2uhsxopva.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2sauzlttj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gt2wdxygkwd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2odqbgeou.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gt2mdjxxlci.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gt2biiaomvb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gt2bxzjgnch.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gt2mlfiizwm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gt2otsrsbrx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2foioszzl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opmyrsrf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2opxvpolr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2atspfalb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrexphad.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gt2yyavcepv.html


<!-- 参考信息 -->