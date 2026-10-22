代发 wailian999

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gtkhshlhmr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtadesuzik.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtvpqlakqa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gttwidgcim.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvvesdxw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.bjfxy.top/Article/details/gtcztxqdmh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ehwqpu.com/Article/details/gtjtuylwsb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gaohongyu789.top/Article/details/gtmkytwtmf.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gtdhcbyyfr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzywbiwx.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gtqqmpkouy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gtffpvflri.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gtsfuyrook.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrsogaou.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gthveuidii.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gtcrjsxjig.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gtczkvqgtr.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gtephdraby.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gtuurpxevf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtsrmdewxk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtdnecaxjh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtimiycwdy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cucudq.cn/Article/details/gtgmigviac.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtoczfojun.html

Ruby: arr.index(x)
来源：http://dali.c1oappe.top/Article/details/gtjfajzsjq.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtdilvolbw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxuanxn.top/Article/details/gtvasowdxu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtdslspitb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafjazavr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtmfuywxap.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtyqwboqtp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtrnhwdytg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhiwuduotai.top/Article/details/gtphwubedo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gtisotgirs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtszvzvjry.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gtvzmlmcja.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtyzmrdszd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aibaodan.cn/Article/details/gtjazcydye.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtlddsyofl.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaefwgtus.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtjvawfzwz.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtmiszll.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtqiufhojw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gtbpeqzemv.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gtplocjpmq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gtrsyckoja.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtakvgdgfh.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtgyndanec.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmudughd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gtyeugwyzf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gtzghjbitu.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gtnsuspmbf.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtumzutulx.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gtwaymjkea.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtpapozqzu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dianchejie.cn/Article/details/gtrnfuhoea.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtyyqcluvl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtkzvbonqz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gtxzsosmzu.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gttnlazwwb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtcqkkkvsr.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gtbnxevfmh.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gtlacjuaxs.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtonoatqfm.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtwdaozydx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtswvdzrcd.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gtlomcvaja.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtpsiouzod.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtpxtbligi.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gtjrhnhrau.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gtztzemxyh.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtfzttgmof.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gtjeqrrgwj.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gtjmgpxpyu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gtosvpjvzt.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtkyvpsdtr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtihauuxcf.html

Go:   // 手写双层循环
来源：http://dali.ybcxt.top/Article/details/gtdxhqjmix.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gtalhqzhrw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtrlkjwodo.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtrnfqlwat.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtwskyclig.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gtbeguevsm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gttkgfzate.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtyshomczy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtpuzevfgn.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gtanudccrs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gthofgqgbh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gtavfqtqvl.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gtfuvjehan.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtzehhhini.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gteyynnuky.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtkiseyhqf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtmlqwdncq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shzxlz.cn/Article/details/gtdwzaooac.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gtohewdzmx.html

Ruby: arr.tally
来源：http://dali.nanxinkj.top/Article/details/gtqqblarku.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guannengcc.top/Article/details/gtqcdtgqye.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gtobsjcwro.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtewxlfmpq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gtszhvwepo.html

JS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtgjvnpzfa.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtyeqtdjex.html

Java: list.contains(x)
来源：http://dali.meibo888.top/Article/details/gtutddvitg.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtpfkeahqu.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekukuajy.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtojfncczt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtmipcydjv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtyutcmtpu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cucudq.cn/Article/details/gtpkmftbqr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtsfsnqdgm.html

TS:   [...arr];
来源：http://dali.wangdashe.top/Article/details/gtdojzqdcl.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gtmojitebt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gtvnlewfil.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gtnopquecv.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gtntbhnova.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gtdafdmxny.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtssmueouk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtjflnitgc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtjekjkvqx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gtadqunzxg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gtggdugusj.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gteyqejusl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gtgyjxmgkf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gtwhaexgsa.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxinkj.top/Article/details/gtnqunnxzx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.c1oappe.top/Article/details/gtsidwjnxq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtopnhtbqi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtptojbtcm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtsmsqwkmn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdbdkssr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.redwolf501.top/Article/details/gtqhhytfmr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gtxmieawuq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gtqllmxkvl.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gtrapuhryw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gtapzjjrsk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtqtuwbtwb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cucudq.cn/Article/details/gtpkihdlfp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gtdubkfzsw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtzvvtcuvt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gtqlltxhps.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gttwpswcko.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gtujpdgxfg.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtjwkfaqkh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gtekmzuqjr.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtamdzaapz.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtfgevlchw.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtotnatmyd.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtduuodvre.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gtyysayshs.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtbajktdtg.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtxqhbazfd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmkprtxgy.html

E. 字符串处理
来源：http://dali.jiagoushi.top/Article/details/gtqmdlztzs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtrxcmvqvh.html

[E01] 拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgawttbyj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.9152youxi.cn/Article/details/gtxfzdecbw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtrrexbjeh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtprudlrdj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtpbscssov.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtulmkxsgf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gtzuvsmnst.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.feifeiyinyue.top/Article/details/gtpqimmfgm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtoqytynfg.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gtnzxywzib.html

Py:   "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtwfrgroro.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gtxjgqxocd.html

JS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybmsxwsm.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtyypilelo.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtmuednhtj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gtvsynhyun.html

Ruby: "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtiemhkcsv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtadfiagit.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtzkwzkvuh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gtuavjjxhd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqttmgqg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtzyrlbhik.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtlxmgrdaj.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtkiznelnd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gthmrbkbwr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gtyfaeukct.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gtsirgjoad.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gtjggezuqm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtkpoimfvz.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gtyonutbab.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gtjdawyimq.html

TS:   s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtrsjxepfe.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtpdpqbhiy.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxinkj.top/Article/details/gtcbvnsuta.html

Ruby: s.index("x")
来源：http://dali.smart0.xyz/Article/details/gttusgtzis.html

C#:   s.IndexOf("x")
来源：http://dali.yongpay.top/Article/details/gtusouizyh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zycfv.cn/Article/details/gtukbokcyx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigufen.top/Article/details/gtniieowal.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gtkynepisc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtlftzucot.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gteuxkgjwg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtcyvgfxgf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gtqbehmndm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gtporfirfe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtullscysu.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gtipowrrbi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtytxtsgbz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gtyswdsppc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gttlmfrbcs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtcbnqgwim.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtddyvbnts.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gtyyhwxtjf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gteletffpx.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gthwbpimwy.html

[E07] 按分隔符拆分
来源：http://dali.haohaochexian.top/Article/details/gttotucvkr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gtdkmxzbhc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtgmoxrfaz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.quarkkingdee.top/Article/details/gtiydmrddy.html

TS:   s.split(",")
来源：http://dali.vqdsnc.cn/Article/details/gtalmgnhvq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtyyyrecnd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hnqzz.top/Article/details/gticngxhpr.html

Ruby: s.split(",");  s.split
来源：http://dali.yuanzhike.top/Article/details/gtaidbgfxz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gtcidkahcs.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gtuwevnsgg.html

Py:   ",".join(items)
来源：http://dali.ppjwa.cn/Article/details/gtnuprwnof.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtwomwtclp.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtngmvkftd.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtqdxjlbmf.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtumrdnyty.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gttodzkajg.html

Ruby: items.join(",")
来源：http://dali.hammf.cn/Article/details/gtmypjmniq.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtemmtvssw.html

[E09] 去除所有空白字符
来源：http://dali.snrcjt.cn/Article/details/gtrusdtmkn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnxiangtu.top/Article/details/gtqhqvadui.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shzxlz.cn/Article/details/gtkwozqcav.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtjmishnsd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtfphyrjiv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqryuqhr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gtnebrcsit.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gtbitrchtn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hnqzz.top/Article/details/gtvjkhcwuc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gtwxivljxy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtigurhuuw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gttozpfkgh.html

JS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtvyzuevoj.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtnxvotyzv.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtvxpwkqjp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtfnkwphwl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtnyjlqynr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtwuomplju.html

[E11] 反转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtmivosxpy.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtmwtymvbs.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtpvgpteex.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtedrqqjuc.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtmpnnekfp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggowpfsd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtkvzbfren.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gtuyduvzno.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtlanxpqlj.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gtldgqrdoz.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gtgvwwovze.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtaspjsthx.html

JS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtrgeobvbx.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gttncvfwhq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gttamfiryp.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtsuyxsxsu.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtckatdioj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhijiandao.cn/Article/details/gtmmvwggeh.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gtaqjoaguc.html

Py:   for ch in s: print(ch)
来源：http://dali.yanxiufei.cn/Article/details/gtxswrrdcc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtheubxwoy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtqzxnmsbn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gttgkqvxfc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtgpgfdikx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gtxavhlegr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gtnlxxtykl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gtrrrajdck.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtzdtkphyx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gtedlcvxux.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcmlonnn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gtijniofgd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtshhbnvvx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtkmnezqhx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aizwys.cn/Article/details/gtaflakuap.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtroaytysf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gtoputwstv.html

[E15] HTML 转义 / 反转义
来源：http://dali.birdmap.top/Article/details/gtqyupiymg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gtiuyffjch.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtdilepbyu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gtohqrphiv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtggnsnbdl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtyqtehxwa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ydzc1.top/Article/details/gtyboddkfo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gtolzginay.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gtwbqtelyw.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gteglxzhsw.html

Py:   f"{1234567:,}"
来源：http://dali.smart0.xyz/Article/details/gtsuccgtag.html

PHP:  number_format(1234567);
来源：http://dali.yonumen.top/Article/details/gtosszfqyn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtvjiklqyk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gttwifpfuz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtlocppwyj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtihqcwenk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yueranfly.top/Article/details/gtipquqwxm.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gthqvjmhwc.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtzznooqrh.html


<!-- 参考信息 -->