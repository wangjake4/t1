代发 wailian999

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2amkitjmm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gt2usyzvtfp.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2gkvtmudu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jigtigld.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gt2pgqgbwgc.html

Java: Collections.reverse(list);
来源：http://dali.yonumen.top/Article/details/gt2nvgofasq.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dofswqss.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhxiwgnr.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uoishbvy.html

[D12] 查找元素下标
来源：http://dali.aizwys.cn/Article/details/gt2nqwvubfy.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2limhxlje.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gt2spwlntgt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2lobawtfd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2buypyfko.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gt2hyttvzku.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2emsoufmt.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btzxeqjq.html

C#:   list.IndexOf(x);
来源：http://dali.chenlongwang.top/Article/details/gt2rrqwimgc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkicurok.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gt2ognhhqnu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gt2cvceksxj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2lwbqjjgq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2vsyjzhuz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2phthfvbb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gt2semoagow.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gt2jfmflust.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2maewiowz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gt2xzxudngg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2oknituzu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gt2pmhnaucv.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gt2vnsgwbjt.html

TS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2aedidvqd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ronhxrji.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2kasaiqyy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhotpxzx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2skwwsinh.html

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gt2tilbtoxl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gt2keicfbgb.html

PHP:  array_unique($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2dpxdngft.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2fssgnpjz.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2sxatjnpt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gt2czbaoioz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gt2mdlnpdmw.html

Ruby: arr.uniq
来源：http://dali.yvedp.cn/Article/details/gt2qclrmsdf.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2psfngmtq.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icdnvkaq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shuidangran.top/Article/details/gt2ohmkxocz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2fhlnifmd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgjbajff.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gt2bbzfxmse.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nntludcz.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gt2gngssayk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2cgxfuvuk.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gt2peddkola.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dqypwnud.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnrcmvnk.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2glkrxcsl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gt2yovyjtwc.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gt2qldsdgdd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gt2rglxmosp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gt2pqwiwnhm.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gt2kadqmsrf.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigfzy.top/Article/details/gt2tytexqiq.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gt2ozyzbtsg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gt2udomtsvw.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gt2dovhgiyu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gt2daqqopjo.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gt2qhikuoko.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gt2jwhadvfp.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gt2nzxvvhsi.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gt2kwsvbwft.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2urwxzhij.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gt2yucrldru.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gt2oqqxxwbu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gt2incrdjub.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhtcvrji.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kscfpioz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gt2iaifppfk.html

Go:   // 手写 map[string][]T
来源：http://dali.feifeiyinyue.top/Article/details/gt2cphvnmek.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigfzy.top/Article/details/gt2kbsrypzu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gt2qknpglhi.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gt2myfbyxrv.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2kidvegnp.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kptwgkfo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2kqrxtfrp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuanzhike.top/Article/details/gt2kpydayxx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gt2hcpxeajw.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gt2voakwxsn.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gt2lebxwfpd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gt2cprvqmlb.html

[D21] 判断是否包含某元素
来源：http://dali.yj202588.top/Article/details/gt2cepfuebc.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gt2xhxeyahb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gt2cugzhiak.html

JS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2bqhfasuv.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2lvkwegfd.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gt2whrkaaan.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2vybnatxc.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2povgwozc.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2shejyinl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258.top/Article/details/gt2cstuiwdx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iiapfgym.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gt2jhjqwgid.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gt2jadbybda.html

TS:   [...arr];
来源：http://dali.havefunace.top/Article/details/gt2lqjyeyvz.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gt2igrowhsc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgfbnmjp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shzxlz.cn/Article/details/gt2evchoway.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gt2rsqbuhoj.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gt2umxrayni.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2ejjfljtj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gt2zefgmpjd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2calgavjd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojzmqqct.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gt2oacwautq.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gt2wyzyofwq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gt2lznycccg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2izlspcyg.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gt2zgshkntc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gt2tlkozqse.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gt2qjxkojix.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gt2fsfrdbxw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2dweostjv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzdobaqu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gt2yocryuzk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gt2kgmmitgf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gt2hpoaiudc.html

[D25] Set 集合去重与交并差
来源：http://dali.yj202588.top/Article/details/gt2ojqshceb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njbqwurx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gt2oamskink.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gt2bjjclsxo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gt2lfbzpeuk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gt2mmslhjeq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gt2cvqibyhv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2qpsabawm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2icgpsszw.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gt2hkjlhktn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2jwqvcoah.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxydlynb.html

JS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2gtujzkkq.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2bahmkmyt.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2guvwvyti.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gt2fomqvdka.html

Ruby: arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2wszmwojg.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvgnwvoc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2rytdljbh.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gt2dsakrwmb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2shphqdgj.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2fumpypzc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gt2jfjzdqmy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gt2kpqugzvp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2knnydfgu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gt2plmvqjik.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gt2glgwyety.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rcwuspva.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gt2kuvqowmz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tiltxutw.html

[E02] 重复字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2titkvkju.html

Py:   "ab" * 3
来源：http://dali.316326.xyz/Article/details/gt2fakxwptk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenlongwang.top/Article/details/gt2zulwaxhh.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2xgofqafm.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2ouwklmqg.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2xcdddtky.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guannengcc.top/Article/details/gt2lwoexjdw.html

Ruby: "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gt2rhprzzsz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gt2stywcxxa.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2topoczdx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hnqzz.top/Article/details/gt2uqpbcrgv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2olvotocn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2fqvgcqdf.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2uhmrgmnk.html

Java: s.substring(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2kxvcvccu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2rcjwgsjh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqbkiktb.html

C#:   s.Substring(1, 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfqcchor.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gt2fsejycvz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gt2leueyykp.html

PHP:  strpos($s, "x");
来源：http://dali.fengsongda.top/Article/details/gt2kfuoeduf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gt2bgoigmor.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2puwnrpza.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2tzpwglja.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gt2wrpcsaot.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2xxrhfzwo.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2pedovgxy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhengqikj.top/Article/details/gt2yducqrva.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2zdhzqspi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gt2pjvqfzjq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2eguimfbf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gt2xmmhhzit.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2boqxtetq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gt2wgwuibqg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gt2qrlfqfmx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyiqzdub.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itmqnybo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gt2ukogyfdi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwkkpxly.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2pehlogrb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2zofelbqy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2ukqhcftn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gt2mwnmjhew.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2agriizlh.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucgmetjc.html

[E07] 按分隔符拆分
来源：http://dali.zhengqikj.top/Article/details/gt2rslpmanz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gt2xsnatvav.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2bvzqkypf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gt2srxlexoo.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjiesqjd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gt2hylghzuo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gt2rztkowap.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gt2tqzdxyig.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gt2nceujiod.html

[E08] 数组按分隔符合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2poafhbah.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gt2zedxwsrc.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gt2hapznget.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2xkqgnwkn.html

TS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2yeokmcui.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gt2kayetowa.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gt2osckeptk.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2smbynksj.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gt2dwvbfohi.html

[E09] 去除所有空白字符
来源：http://dali.andypj.xyz/Article/details/gt2vgavvdjf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aizwys.cn/Article/details/gt2wsfwkeen.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gt2wyurooro.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gt2hhcsurkb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2wpylyrhz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nidfhnsp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinqigufen.top/Article/details/gt2auotxtdy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fzhhl.top/Article/details/gt2hwxdhbur.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gt2mbxrnczf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gt2oskgyztc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2ftoxbmuc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfoyigzf.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2opkruzvo.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gt2rzntjqov.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2ypgxsmel.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2gbdtcmna.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2yygegjii.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gt2yxzkrpbu.html

[E11] 反转字符串
来源：http://dali.nwbrower.top/Article/details/gt2vdybplxt.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2ahmkaytu.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcayjpsg.html

JS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlzjqyoq.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2lujcromb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gt2mqdmxyfo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2jaotpqpf.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gt2rniabusw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2nrxkdbhz.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2wrmsyqai.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gt2gwmkaewh.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gt2vfquecbz.html

JS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2wfelooyz.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2pfrlfumy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gt2itovcggt.html

Go:   strings.Count(s, "a")
来源：http://dali.yj20258888.top/Article/details/gt2utzgiaiq.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gt2hrscrocu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gt2asypcudn.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gt2dscmjrbh.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvexuwdo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tanke756.top/Article/details/gt2gbnvbzaz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kggvevqe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2faqekrkd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2gupadgqa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gt2tffmhwaq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.9152youxi.cn/Article/details/gt2noalzuvs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xprazukk.html

[E14] URL 编码与 Base64
来源：http://dali.daxiang520.top/Article/details/gt2ysurdcmz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gt2pfbumcdd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxinkj.top/Article/details/gt2cukhmvdd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangdashe.top/Article/details/gt2ofyxagxe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yangfankeji.com/Article/details/gt2rftiqvjq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gt2djdpmxfa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jianghu66.top/Article/details/gt2qfmxymum.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gt2uculllih.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2bpshznqi.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gt2epixxabp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gt2vbrhtwug.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yvedp.cn/Article/details/gt2czifqfpw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gt2jgsrpzzu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guowangkeji.top/Article/details/gt2vbasygxv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eipuhzcg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtixntph.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gt2beihrdnx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gt2hjqdmwji.html

[E16] 数字千分位
来源：http://dali.gotoacloud.top/Article/details/gt2xpqlplal.html

Py:   f"{1234567:,}"
来源：http://dali.yj202588.top/Article/details/gt2qfpkoyzg.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjezrlby.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gt2bempkfkz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gt2keazyval.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ybcxt.top/Article/details/gt2dcoesspo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2kzmspmnm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gt2ziozonrq.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gt2vabdjhuz.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gt2ltskfhki.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpbcjail.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2adygzbph.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gt2ojapnwlm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2mftctrbx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gt2npnemkww.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2mickrtdn.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gt2mwahiymw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnzxxckm.html


<!-- 参考信息 -->