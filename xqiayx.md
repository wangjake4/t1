代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtezmwgplz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznrfpkaq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigfzy.top/Article/details/gtnlbqxqlk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gtaejpnleo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtgwbuvnwh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtgjqtbgcw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtcjnugnnn.html

[D06] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtotntnqil.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtglbarxfe.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gthasxwszv.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtcnpnmceg.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtitbxutio.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gtnihgzqgr.html

Go:   len(arr)
来源：http://dali.yj20258.top/Article/details/gtosmrhhju.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gtkeacxeak.html

C#:   list.Count;
来源：http://dali.hfpthk.cn/Article/details/gtocjmxozz.html

[D07] 切片 / 取子数组
来源：http://dali.gaohongyu789.top/Article/details/gtvfsyfueq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtphicgeev.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gtixkdgdch.html

JS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtjjtmunmq.html

TS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtgotbhpav.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gtdiekkhea.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gtrsjpvnsc.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtbghehypz.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gtnvnkzrde.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtrqomhuso.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gthtwfytug.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gtoudqzkxb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gtmhtyneju.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gtxtamlulx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gtxskefphr.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gtqepcxgoa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gtanhhfesf.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gtboysdrrj.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gtdqofidwg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtgksczpah.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gtdeedoynk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkakknmj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hammf.cn/Article/details/gtjgfzdcwj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gtmislsmqt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtixxheeqp.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtqqnuqnkj.html

C#:   list.Sort();
来源：http://dali.xuetiantiany.cn/Article/details/gtiqlsuvgp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gttamcucpk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.iojbl.cn/Article/details/gtgkwrfwdz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmksufkgj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivjiszsp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gttekdfawy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gthqmjbrtt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gtpqzndygk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gtbujjdtvm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtaoaojblc.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtypaoqwhw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtkleghjby.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtfwceqtdy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtuaxdocik.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtgvgomytf.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtqxvfqlmp.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gttkynakyn.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gtajcsgqoy.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtietwwqca.html

[D12] 查找元素下标
来源：http://dali.cashguo.top/Article/details/gthieagvon.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gtjwbmczhd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjgtjels.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtvnacxjks.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtmbunxuan.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gtoewwxtvy.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtmlvqpcol.html

Ruby: arr.index(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgatzhwo.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtnacirzmm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gtyvatzmyy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtrvhpcpzv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gtesdixymn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtdngebelg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gtmmyxqnpx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtajnwmpte.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtvjigdsfv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtkanjgsre.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbgodnej.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cheryme.top/Article/details/gtntnisqkv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtgolucjpz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtilblsqaj.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtpoyvllib.html

TS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtmrduejam.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gtxfliqzva.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtwofwyxmu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gttdrexwjk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gtmmjaqkil.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gtuiekeotg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtjrbdrfko.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtjpmkyeoo.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtgnjbqums.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtgddwdyuh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gtoepstflq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cdnleiting.top/Article/details/gtkopusghj.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gtckyrxhil.html

C#:   list.Distinct().ToList()
来源：http://dali.hnqzz.top/Article/details/gtquybznjt.html

[D16] 求和与平均值
来源：http://dali.jlsjyb.cn/Article/details/gtvczdrzxz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gtysksmnts.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cheryme.top/Article/details/gtxcgwnsqv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtyzrwiogv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtfvddoazk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gaohongyu789.top/Article/details/gtrmgfxvkd.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtzlpwrhuy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gtyhejdcfu.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtguozlghl.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtsvyqchqp.html

Py:   max(arr);  min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtdgalcghv.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvfgsqwi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtnwanebru.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gtrmsdrhjn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtznixxyal.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtcbdabnmq.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gtfzcdstsh.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gtnycdydfz.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gtakabxckt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtashjexqo.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gtzqubsolo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gtxpxcmopn.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gtgrrubieh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gtaljjtbka.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gthtnuteat.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gtgawtdmwf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtlzhfimpe.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gtzatksbhv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gtvrmxjpcr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gtexkzfmco.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gtqsagkzfr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtjxueqdmk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtnwxmbwsk.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gtiiwtphof.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gtwtbdtnii.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hysaishi.cn/Article/details/gtnmrfyiwd.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gtdwimdoxt.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtucxyfaol.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtylihohoo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtpzfmkngd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtkleqbvqf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtosumnwhp.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gtddrozzmg.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gthhxbosrf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gthurjpafa.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gtgvqbbtmm.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvucgyasd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtcjbdvzil.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtyvsdirha.html

TS:   arr.includes(x)
来源：http://dali.pycfn.com/Article/details/gttwtpbtew.html

Java: list.contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtfgzmbjhk.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtnuytewnf.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtxfpiarwm.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtateedgpr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtvwikahnu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nwbrower.top/Article/details/gtnaomjrxt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gttoatzirh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gthlwhudva.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gtgunxhocq.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtjbfeqgax.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gtvkgjruux.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gtpqlfidxs.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfikrhvsp.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtzroysouj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtderwugmo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gtdzoojtur.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtuxnokpsk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtjeyeptku.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gtvejgefdm.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtxauqoklh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gtamodeqwd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gtjcrpejye.html

[D24] 字典 / Map 基本操作
来源：http://dali.cheryme.top/Article/details/gtkvlxgyqk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gtzxvljkyd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.birdmap.top/Article/details/gtvqqbryeu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.andypj.xyz/Article/details/gtvhcsqorh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtopglsqkq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtrsqymsdr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gtrcjvjypd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hywenlv.cn/Article/details/gtfbabubgz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gtrtgooblc.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqbieqsb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gtkkyfwlzy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtenzivalx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.9152youxi.cn/Article/details/gtopeedysq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ybcxt.top/Article/details/gtqjygdyyr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtzsmrnqcx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gtfpakbzzu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gtoqlwixtt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fengsongda.top/Article/details/gttnbyunzq.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gtbbnoshdp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtnuuhbmey.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtecmipemw.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtlleziixm.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtcxseydhm.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtugvctmje.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtdzmslzlu.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtpzusjniw.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gturrzydzs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtunqlpfjb.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtmmlvqmjo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdlhvjdiq.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtnxfnxjdl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxuanxn.top/Article/details/gtqamgtmtb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gttjyenlrm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtjtwdgbgs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtbcoiilus.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gtmdygybzx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.iojbl.cn/Article/details/gtddocazph.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjiqejssm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtajixjxgw.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtkflczwon.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gttovmnlla.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gtdxvhtzsb.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtdhgzgack.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtfhmohsob.html

Java: "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtyauicegq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtofqhnnwh.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtkurlhzjq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtvtzoyjyn.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtkszhoheo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtugzyfzbx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtbizbzeis.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtvhsttpyu.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtxgbarymp.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfinhqjgc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtdydptqmo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gtqfhbwlwd.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gtrwoljhio.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gteqdyihhr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlpmvkhz.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtdtskcrru.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tian-w.cn/Article/details/gtiswnuzuo.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtbohlpgzj.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtwmcaayjc.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gtmiqsckxo.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtshecfzxa.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtthpvpmtk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gtlrjnntep.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gtulucugds.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.kuanghao11.cn/Article/details/gtyormdwma.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtxwtkorrp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gtvfjmqvpm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtvjninhqx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ydzc1.top/Article/details/gttmiswcrc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gtwsiaqmrp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtmgnhlliz.html

[E06] 替换子串
来源：http://dali.jyoumei.cn/Article/details/gtyfeibade.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtegqwzxgc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cucudq.cn/Article/details/gtcqwxizjh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtaeejnyqm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtapxegjtp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtqcjhiilw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gtqxgjuidj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtciuglmsu.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gthhhtzyif.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtuyxyflxl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hywenlv.cn/Article/details/gtgvtfnguq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtgodeeeez.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gtmgvacoel.html

TS:   s.split(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtkgwgdoyf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gtwfluaogs.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocyhhicx.html

Ruby: s.split(",");  s.split
来源：http://dali.yj202588.top/Article/details/gtezjbefkc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gtpyddlbou.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtpebxfmzn.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gttxaslfin.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gtdokaccfa.html

JS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtinkjzojs.html

TS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtvguexpvr.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtjkixkfhz.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gtvkvzobnc.html

Ruby: items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtuqyldtgm.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gttgdewjnf.html

[E09] 去除所有空白字符
来源：http://dali.fzhhl.top/Article/details/gtaumzibcl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtbsxghnxh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.bjfxy.top/Article/details/gtwbkuppwk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gtoataanqp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gtfmpypbwt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtzsccmdec.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gtfkqqhvpd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gtkewnjmoh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtbgnbrtqm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gtbvlztlzx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtcufncmul.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gtqjuypuaj.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtibvosfxd.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtsyfkdank.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtepkcbvqr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtwucisxry.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gthcsdizqx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gtikgvweor.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gtvtyirpdu.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobwbqdwa.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtrwlzoamp.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtnewebhsx.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtzcbmwbjd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtsnbzqbxu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gtosqelulq.html

Ruby: s.reverse
来源：http://dali.sysykeji.top/Article/details/gtlktedamn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtesfpaotx.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gtfqyhyvfn.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtzicqscei.html


<!-- 参考信息 -->