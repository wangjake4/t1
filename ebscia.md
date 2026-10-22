代发 wailian999

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtkgafsgki.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gtlrbokyqn.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gtxxkstcwt.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbtdekcl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gtruhzkjrq.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtslnereyr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtlmwdnsry.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gtqmlttwdk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gtkyinclse.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gtertqfdfh.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gtitcsojft.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtghhohmiz.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcitscffw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gtlemyzxbd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gtvbijqvab.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnxiangtu.top/Article/details/gtylkstkfv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtbtwaalth.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtmxhjesyf.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gtagqvubnm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258.top/Article/details/gtgluwxqme.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gtaazcrike.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtgupyxfvb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtaaihckhr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gtqtkkaixu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gttgphpimi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gtkthmnmxg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gtnmuaxizn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtzhcwkpto.html

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gtowytubrr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gtdmyfqard.html

PHP:  array_reverse($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtmgxctqbk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj202588.top/Article/details/gtwihjdbtg.html

TS:   [...arr].reverse();
来源：http://dali.sysykeji.top/Article/details/gthmkteixu.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gtzitmgggz.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqidbjen.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtlefizuzt.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gtfbiyvamv.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gttpuiweub.html

Py:   arr.index(x);  x in arr
来源：http://dali.pycfn.com/Article/details/gtkzyenyxe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtaocwomeb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtnoxnixuq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gtjccxlzfv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gtstpolmlj.html

Go:   slices.Index(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtpfyvcaba.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gtlmznzamr.html

C#:   list.IndexOf(x);
来源：http://dali.sweek.top/Article/details/gtgvooijkq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.c1oappe.top/Article/details/gtwpezmuhg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtyskjocbk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekrcqlzn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtuzxkoffu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtuswobqyf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvotbynis.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtykdzszoh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj202588.top/Article/details/gtcliqprvr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xinyue.icu/Article/details/gtabsgkeoe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.andypj.xyz/Article/details/gtubkyevhs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gtbvpvxisx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtfdjhzvhd.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtuvfyzxju.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtsmooweso.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gtxsfckfll.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtzrwifaqo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtzcgtwzkr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxvmnspu.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gtamkrzkli.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtcvpmainj.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gtlbpssuoc.html

JS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrbrlqel.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtaffxgfzw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gtpzskdrbd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gtexojsfid.html

Ruby: arr.uniq
来源：http://dali.ydzc1.top/Article/details/gtogfvfzwv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gthgxzpgsw.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gtpavencbu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gtcfvmxcdf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtpfncxfxc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafegczmz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtmbmjqxma.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gtcmbgkfbx.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gtsuzmcimb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtsqrtyyvy.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gtvkaqcfno.html

[D17] 最大值与最小值
来源：http://dali.jyoumei.cn/Article/details/gtgkyzalgh.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtkdtxebfm.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslxrjcwj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtdpxjabzq.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtfvrbitpk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gtyiglacgz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gtpwbykxrr.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtwvgbhfam.html

C#:   list.Max();  list.Min()
来源：http://dali.9152youxi.cn/Article/details/gtszuadqia.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gtzqupujpw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuanzhike.top/Article/details/gtkufuxoqg.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtzpwwpdyb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gtxlyfyqdd.html

TS:   nested.flat();
来源：http://dali.yj20258.top/Article/details/gtdhtwcjzq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gtzddjvomx.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtmclncqew.html

Ruby: nested.flatten
来源：http://dali.jinghuilouyu.cn/Article/details/gttrzbjkeo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gtswjlbcur.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gtrrmxiymo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangdashe.top/Article/details/gtumyxwbuu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gtcccoauyb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gtfbagynsz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gtzeceadnf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gtbcbzrmmj.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gthkhbsilx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gtuvsnwayv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gtzubvvfoi.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gtvcqfnpan.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtfsevxdgf.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtfjiolxad.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtqahbgczc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gterihgghj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gteeuegqka.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtkxurkdyl.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtyrulnnmb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gthpolupoj.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gtiomrquez.html

Py:   x in arr
来源：http://dali.yj20258888.top/Article/details/gtiyalyeyu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gtvtwhsnoo.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtultisady.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtcymtgovg.html

Java: list.contains(x)
来源：http://dali.ydzc1.top/Article/details/gtxrmsaayj.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtkvujtylx.html

Ruby: arr.include?(x)
来源：http://dali.xuanzx.com/Article/details/gtbiuvecpf.html

C#:   list.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtbzildwai.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gtqdsjlfzs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gtqhcskatr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtttuymhhm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gttmmfomuj.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtuwiknbom.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gthwvtiumj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhixingplan.top/Article/details/gtivyirqlu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guannengcc.top/Article/details/gthkkwcsdj.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtdfpmesrb.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gteawuvxro.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglcwrcde.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtyiholmzw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtrjraukwg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gtlfxlgige.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gtorndnlxc.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtagtdyaer.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gtctizxowh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtjtrmuvlx.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjldqxll.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gtrbpqvppc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gtkicymaso.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gtxgabacya.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtzhzzeqzn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gtqmwpphtj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtmtyekwtc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cqqwz.cn/Article/details/gtwvowrsci.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlshekmgx.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlxczhpv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gtfbmyqkvw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gtcykxibtq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gtumwgziav.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtvmslaggp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.fengsongda.top/Article/details/gtbftxngjv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ydzc1.top/Article/details/gtmoqtezni.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gtrcmabdgh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtmuosyiqn.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gtwevdidey.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gtxkdwaeqw.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtoxmmelit.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gteawguvbz.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtxdgzdols.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtnucdtspq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gttbwifdvt.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtwfyoiend.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtcmpehmwq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtiqoeeohl.html

E. 字符串处理
来源：http://dali.9152youxi.cn/Article/details/gtmaerwdtr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtquzdvsbx.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwxmobbj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gtcxbopttf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gtvxohhggw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gttmdaxeui.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hammf.cn/Article/details/gtdievwtvu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gtxkdcdlzh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gtkadngkrj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtbzvmybdo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtiisjxnsx.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gtnuwpfujg.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gtjkccifud.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gtafazcfna.html

JS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobhprxzj.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmicqeppr.html

Java: "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtjirwlnog.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtmovljjtp.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtzhhjklfg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hfpthk.cn/Article/details/gtslgrvmkf.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtkucbhmnr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gtfyzajfgz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixpcfuqb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtkqslsntd.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtkncziont.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtkbkbiskb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gtjzofjpgb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gaohongyu789.top/Article/details/gtzhlbcioi.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gtbtsbkyfg.html

[E04] 查找子串位置
来源：http://dali.pengpengdd.cyou/Article/details/gtjwdsyeel.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtsyftcywx.html

PHP:  strpos($s, "x");
来源：http://dali.dianchejie.cn/Article/details/gtryaeuwzl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gtcqbsrmjq.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtultpkoaa.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtnbeoaach.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gtsbrbdids.html

Ruby: s.index("x")
来源：http://dali.hnqzz.top/Article/details/gttzwooswb.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtrmtaeoyp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gtariruxjc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gttemarqff.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gtsuulvhpu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnqzz.top/Article/details/gtflhzmscd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guowangkeji.top/Article/details/gtqisedfvg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtzrrpxstm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ybcxt.top/Article/details/gtovogrzlf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gtgkeprqib.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtvsflptqr.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gtphguzphj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtgqkdpulm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gtdwkxcqqu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtwstvzhky.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbfofepr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtgxfnwvvg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtvaiglbyz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtwifizppy.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttmbntyd.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gtztergzze.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fengsongda.top/Article/details/gtkxwjymnz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdweehfor.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gtkxkfkrrg.html

TS:   s.split(",")
来源：http://dali.xuanzx.com/Article/details/gtjbrcjbof.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gtartyrjvp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgufenzy.top/Article/details/gthhgtqxfz.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gtvbryvdgb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gtmfmpskyr.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gtgmbthkzi.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtbiizhrhk.html

PHP:  implode(",", $items);
来源：http://dali.xuetiantiany.cn/Article/details/gtljmaania.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtuptkcmyi.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gtwevpspgr.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtffkrypwx.html

Go:   strings.Join(items, ",")
来源：http://dali.zhoulong.xyz/Article/details/gtkivnibhl.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtwnppsekh.html

C#:   string.Join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtywoewace.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtcuqyujbf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gtoshnxvtq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtbxcklund.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gttkxetnvt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtsytiqdim.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gtalhakkna.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtogzzqlde.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gtspfborrx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtnxvmtrwc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrugltcu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gtxvyrpwvv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yonumen.top/Article/details/gtilscrjlx.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtmuhtxhyr.html

TS:   "7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtmvkplszs.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtqcgnjtiv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtcsmeyijn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gthdynobxs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuetiantiany.cn/Article/details/gtgutfpxyk.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtbqslivmg.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtuthfjsdo.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gtpoocniil.html

JS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gttcisinbg.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtkzhxklpm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gtkrpgedyr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xziqi.cn/Article/details/gtilqknuaq.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtenzbvsrv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtzudrkyzz.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gtpsojkupx.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtsuqwtgit.html

PHP:  substr_count($s, "a");
来源：http://dali.xziqi.cn/Article/details/gtchuyfuzv.html

JS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtfkhjyxuz.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gtnwuqbxgr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.pycfn.com/Article/details/gthovapizw.html

Go:   strings.Count(s, "a")
来源：http://dali.tian-w.cn/Article/details/gtsfvtgste.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtwrbpqtfo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmfissjb.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gttpywbhud.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gtdmfcwdrs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtchczqmfb.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtwjpfyxme.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj202588.top/Article/details/gtvpprleai.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.birdmap.top/Article/details/gtvzzumhmt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gtddgltvwj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gtkpzoapyh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtzuejsnum.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkskshhm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.dashuyun.cn/Article/details/gtahvcdycw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuanzhike.top/Article/details/gtkjpfqbuh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtzwtzseep.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gtpkcnnlnb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gtxflvpfjc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtzerwsdcg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gtmkqdroqj.html


<!-- 参考信息 -->