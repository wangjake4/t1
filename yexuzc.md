代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtyqupswgm.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gttectyxfd.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gthadgvohf.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gtqhcplksr.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gtmxlsulka.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtsfbbdzve.html

Py:   arr.index(x);  x in arr
来源：http://dali.tanke756.top/Article/details/gtkndvdepe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtardaqjmm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtksyfyibg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtscspdpgg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtouqesjjw.html

Go:   slices.Index(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtvqshjylf.html

Ruby: arr.index(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcrwfmkr.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gtsoryltui.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuetiantiany.cn/Article/details/gttpawosgb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gtmdbmiosi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtnbvparqs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtpewafxkl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtcdnsdwdn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gthlsvoblp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.bjfxy.top/Article/details/gtrjcavjzy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenjidiqi.icu/Article/details/gtugfbjoyp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtzgrgonby.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnxiangtu.top/Article/details/gtazjkbpll.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gtzvylkmxt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtefzwdtga.html

JS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtolieneif.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtuvbraicm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtuduyvfsi.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtddpfusgt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtrvflkqjv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gtnipqproz.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtktdgykgn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtkwxtttxs.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtjhyatjio.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtoeqnazav.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtuscjzucx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtdurgznra.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gtbvqvswrg.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtqilzcqap.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gtvryvtukf.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtdkutlykh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gtdeowfnah.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtoyvxyvah.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtsujsjgav.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtjhiiiuvs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gtvgtwziwn.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gtztsbcywh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gtgydwqxth.html

C#:   list.Sum();  list.Average()
来源：http://dali.316326.xyz/Article/details/gtkntycbra.html

[D17] 最大值与最小值
来源：http://dali.sxryk.cn/Article/details/gtycgrkpyn.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gtaasmygly.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtzyoxechy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtraxedlsm.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtsufqswmw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gtdoomphls.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.c1oappe.top/Article/details/gtfxgbgfus.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gtblidmbqo.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtxpqiggaw.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gtjnlobplk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gtvrpultqv.html

PHP:  array_merge(...$nested);
来源：http://dali.gaohongyu789.top/Article/details/gtvjahqlrt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gtrkbysocn.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gtjwqeokbn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gtlrdjsban.html

Go:   // 手写双层循环
来源：http://dali.guowangkeji.top/Article/details/gtobsbkzlm.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gtevnqwije.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gthfuvrvau.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtzftsioza.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gtarpcwekx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gtvkbaskqh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yonumen.top/Article/details/gtgogjuwkn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gttllzpgwq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtbhoywqhp.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdayrskth.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gtsxoetuft.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylaedkyo.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtlllrkvcn.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtygfpcbab.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtbkhrvzqr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoknycscl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtaqtjyfsr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gtrymykzdq.html

Go:   // 手写 map[T]int
来源：http://dali.gaohongyu789.top/Article/details/gtntcqlkpo.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gttysvozbg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gtplsllokf.html

[D21] 判断是否包含某元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfgekgom.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvpzyljd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqviatoiq.html

JS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtkogvhrmx.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtjwhcoyss.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gtkncnzrbm.html

Go:   slices.Contains(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtpkdiutzl.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtvkwillae.html

C#:   list.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtwjglltin.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtrvwcrwfv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gthkboocag.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtrfwjpuoh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtvxgmuahz.html

TS:   [...arr];
来源：http://dali.yanxiufei.cn/Article/details/gtywxwdzuv.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gtlgdudfnk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkuziozp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gtmuibxrbz.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gtjorqyeui.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtnxajpmbp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gtjzpnycls.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gtsareqxwz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtpexldrlr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtmjzfbvlo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gtwdbeqexo.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gttbazfhpv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.9152youxi.cn/Article/details/gtdagqhdie.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtoxhkbcwv.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtqwkdnlgj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258.top/Article/details/gtjhlecrwy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtcuyolnbh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtezftjamf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtrhaciktb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gtgxxolzei.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gtfakmwbvj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrswbcbsq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gtbhprooxe.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gtzegtclou.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gtcinqrkhv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gtmkigyrow.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ivvv.top/Article/details/gttquzbpjl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznyslyjr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shuidangran.top/Article/details/gtlfmljzhd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hongshengwenyu.top/Article/details/gtartiiivu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtrttyxyfg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.andypj.xyz/Article/details/gtvhgagbnw.html

[D26] 数组转字符串
来源：http://dali.fengsongda.top/Article/details/gteblfcdnl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gtamjghttq.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gtalephfmz.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtkvdcntbh.html

TS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtepgsjplz.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtmeresrwk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygukhguu.html

Ruby: arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtaemsifpw.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtcjkymwtj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtetogjchp.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtqtpbozif.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqjthfgiw.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtnhazjchx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtfcsuaorw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtjljpnqtu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtrwosufef.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gttkqgtytu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gtkifqtmpp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gtotdqsdhl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yonumen.top/Article/details/gtibjjaoro.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtdiwwgeyp.html

[E02] 重复字符串
来源：http://dali.jianghu66.top/Article/details/gtbeebbftv.html

Py:   "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtllqvlelh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gtafhfxxlq.html

JS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtgxcznyuy.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtisahqhtt.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtgzypnwve.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zdqjudy.top/Article/details/gtbgagwosc.html

Ruby: "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gtklwsdnpm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtmtvyguth.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbscxazi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gtylmrlrqe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtqdzyyymx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.aizwys.cn/Article/details/gteoceqtkj.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtzrcyajvy.html

Java: s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gttntcqiss.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.meibo888.top/Article/details/gtguxfkjjo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gtctmcrgem.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkrgwpdn.html

[E04] 查找子串位置
来源：http://dali.tanke756.top/Article/details/gtqssxpmlo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtbpkymxac.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gtvapjjnwi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hongshengwenyu.top/Article/details/gtksqobdwr.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtdlwkvzqw.html

Java: s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gttpaievub.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gtucrusenq.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gtdjhpeizd.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gtisircjva.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gtdskevlfc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gtpmaytvvh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jianghu66.top/Article/details/gtyxbvbzih.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gtdtstffcw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.pycfn.com/Article/details/gtkafsjxuf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtcyixuion.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gtphxpjvtj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gtyzpudcqe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gttzjfjley.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gtzwhthmim.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtdpwgfrya.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.havefunace.top/Article/details/gtivqzlrai.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtfpdjcgmy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhlbgsfu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtwzyjwiti.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtufaujkce.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtltkpkmlz.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtmqyugfds.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gtgmljhavh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.redwolf501.top/Article/details/gtfkoxeomw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtfrhczsdr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gtcoapsmaa.html

TS:   s.split(",")
来源：http://dali.yongpay.top/Article/details/gtnkizapvr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cheryme.top/Article/details/gthpugodpl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gtddhspidb.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gtldosoost.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gtkfkfzxgo.html

[E08] 数组按分隔符合并
来源：http://dali.hnxiangtu.top/Article/details/gtqjihphbt.html

Py:   ",".join(items)
来源：http://dali.pengpengdd.cyou/Article/details/gtecouqqnv.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gtchunjupm.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtcesebppf.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtqscpmhpc.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtvuyieddb.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtplgpnxbm.html

Ruby: items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrajgeiwb.html

C#:   string.Join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gtjezxusik.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gtvzwkljdn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gtfqezerpn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtcoidgrxl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvfetlye.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtknzyamwr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcuechdx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yanxiufei.cn/Article/details/gtivklqqbo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrzbvaai.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtgpdnfsay.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daria6918.cn/Article/details/gtvacngpuj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gtdknmxzfb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gtljjjfcqp.html

JS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtlhmmgmkj.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtyfvhzwla.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtwrlqjtkj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtediefibq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtgbfyjaat.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.pengpengdd.cyou/Article/details/gtdimtzdgk.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gtasecibnl.html

Py:   s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtffciwouz.html

PHP:  strrev($s);
来源：http://dali.havefunace.top/Article/details/gtqgwuszvc.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtuisatmzj.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtpwymwwbp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gtdcifxlbg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtdriuifnw.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtmavtlkvr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtchoolzhu.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gtspvwdjbf.html

Py:   s.count("a")
来源：http://dali.9152youxi.cn/Article/details/gtlvdcvnvj.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gtmufcaell.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtsvecvitm.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtuywoytzi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtwcyaoiir.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gtvzdarpiu.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtosdgfsof.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gtzansmflh.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtwmkwrvvh.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtgcmshnha.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gtnjruzuhr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtduxxfrzo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtoyyjnkld.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sxryk.cn/Article/details/gtbuqagzfn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuxming.cn/Article/details/gtvzytcvop.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigfzy.top/Article/details/gtkvgrkhfl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtoumrksov.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gtwvujhqnd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jlsjyb.cn/Article/details/gtvdrrsgmc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gttwkfxsxf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtzydaxxwb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtavmpwtgw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gtrrljeaxv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gtqrvysklc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtedoyabke.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtrmqadwoz.html

[E15] HTML 转义 / 反转义
来源：http://dali.hnxiangtu.top/Article/details/gtdqpjcjub.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtdkbzfynb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtnzhtadyw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ivvv.top/Article/details/gtgbmmxsax.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtffvynlyc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhongyouzk.top/Article/details/gtxgrezxir.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jiagoushi.top/Article/details/gtwhoykamk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoyrhnns.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjlipkour.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gteyobkzjq.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtvkjhzftc.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gtfkrgbzad.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtnkorhnzj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gthktdbbaj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtqpejytss.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gtaecrfglr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jiagoushi.top/Article/details/gtfgaaboby.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gtbfsupgvu.html

[E17] 首字母大写
来源：http://dali.yanxiufei.cn/Article/details/gtblyrsgjb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gtjyqysyub.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtqvtyersy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtawapypaj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtipatwfvp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gtdzyaqdjb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.snrcjt.cn/Article/details/gtqnmwcjal.html

Ruby: s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtdzyllsjp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtklnhigth.html

[E18] 模板占位符替换
来源：http://dali.ydzc1.top/Article/details/gtvbzufzsv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gtgzuwyoit.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gteojzcetw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtxobkuage.html


<!-- 参考信息 -->