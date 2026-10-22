代发 wailian999

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtonccfxmm.html

PHP:  count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtibamlfsy.html

JS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtvyrxqarg.html

TS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtfzcrlnza.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtmytwrhlx.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtzodwhufu.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gtjithcxia.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gtdagumsmg.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gtaboeidpe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gtesmnjnmo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yvedp.cn/Article/details/gtsjuniews.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtepllpigh.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkgyeink.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gtgazwxmui.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gtmxhwcdwj.html

Ruby: arr[1, 3]
来源：http://dali.jqgfzy.top/Article/details/gtdmwhycep.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtxbjmlird.html

[D08] 合并两个数组
来源：http://dali.sufxvd.cn/Article/details/gthxdqqnup.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtxrqqxzsb.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gtosogdtsj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtradulwhs.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyrpqcyp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aizwys.cn/Article/details/gtmlkdoaor.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gtmlamdygk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gteppjwapa.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtpohvqwrg.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlslcjfmh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtdzljeipy.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gtmtzewwpw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gtjchfikwj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gtxgoltcjr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gtxyckugib.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtkqcfskdk.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtnccggltn.html

C#:   list.Sort();
来源：http://dali.wangshuangyany.cn/Article/details/gtzrhbxbfx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jianghu66.top/Article/details/gtdrxurhul.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gtamcfrksa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtdejjivtm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtsgdgnbvg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtapbmmqvk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtahftqxup.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cheryme.top/Article/details/gtijkcdtpk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fengsongda.top/Article/details/gtpuvwiiop.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtapamndea.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gtssbandco.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gtwhtkzotr.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gthovwimzi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gtzzatgdef.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gtifkdyzfn.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtbsleoebg.html

Go:   slices.Reverse(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtaqtwaohd.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gtkoxvupft.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtkilcjiea.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gtpxqwhhnv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gtjdcpqljh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtrfqawonw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtttcrpkmb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtbbeprrny.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gtbsxwdpze.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtjntjqieb.html

Ruby: arr.index(x)
来源：http://dali.wangdashe.top/Article/details/gtynwixuvg.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtlzgbfbez.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pycfn.com/Article/details/gtyxzvitdj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gtyzwnctdp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nwbrower.top/Article/details/gtdzfewzoz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtcofejnho.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtgcbfnudy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtxckyphie.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gtktktjvsx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gthngxnciq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gtlpbotodp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gtpzhjmbfp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gtchsxllph.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtdichhjen.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtpwyjrqwg.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gtxqjurnla.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gtcinozmjr.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtwplhsgot.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtpovsmzuw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.meibo888.top/Article/details/gtzaptnduz.html

[D15] 去重
来源：http://dali.316326.xyz/Article/details/gtrxkdsswj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gtfqtaprxc.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gtfuznyzeb.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxejdutj.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtzwbkjjis.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.vqdsnc.cn/Article/details/gtrhansiqm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtvqsaijkm.html

Ruby: arr.uniq
来源：http://dali.hnxiangtu.top/Article/details/gtsohfkcbs.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gthoervjbg.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtrcmezgbn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xinyue.icu/Article/details/gtpamwzsmn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtafzjaooe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtqcggcjji.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtgzzgejgt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daxiang520.top/Article/details/gttqcmdyki.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gteegsqdla.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtzkpmiell.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigfzy.top/Article/details/gtuttvhutk.html

[D17] 最大值与最小值
来源：http://dali.birdmap.top/Article/details/gtchgqhkuv.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtcxxongft.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gtibckxulq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gtmfnvwqhb.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtkejjkwiz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gtuucalqqj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gtbnzcyfks.html

Ruby: arr.max;  arr.min
来源：http://dali.andypj.xyz/Article/details/gtlryfvshe.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gtkcnyzeln.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtfwkgrnbi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gtaiqtcehy.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gtwemdnibq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.316326.xyz/Article/details/gtuzifoetx.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gtrfhubvzz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtailflrct.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhtnidqk.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gtwobjcmei.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtmgyygrur.html

[D19] 按字段分组
来源：http://dali.daria6918.cn/Article/details/gtiujtajgb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtsgujvcyk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gteuvummez.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gtjfysjypq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gtvkaqqbuw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gtcqcimuox.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtuhdlhpmo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258888.top/Article/details/gtpzvgqsym.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gtgkvnthlg.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gtbxwlygrs.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gtxvhdielj.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtmmnxmgjz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtndhdlxtm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtjwpwnecs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gtxtdjiswa.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gtvplspohj.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtslmyybga.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.bjfxy.top/Article/details/gtecuohuwo.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gtqmpwgamn.html

Py:   x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtdkyyqzqr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtjqrynymn.html

JS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtkejpsunw.html

TS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtbrukqyix.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gttkpesxte.html

Go:   slices.Contains(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtdjjjsmzl.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtghjbelpf.html

C#:   list.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtzlxmnsxo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gtdajpbpun.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gtvcdjdtep.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gtsxcznyby.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtocrklcsj.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtkmxbhnad.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gthyjryglt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtlnqsvzue.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysszxplf.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gtiupkqssj.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gtuyfwnlqp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjuzuaoi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gtolxwzzkm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtbnrdlehw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtesjbgmqt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gtawkcmybc.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtofgukmmp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gtbgkebabx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gtuynnyofi.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtbmdubivi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdaiepdgc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gtvptdvonu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gotoacloud.top/Article/details/gtvrxfsztg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtujtkdeoa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gtewtoqgqd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gtzrrudjfd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtwiqtkfni.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shangyingyoupin.top/Article/details/gtdqnpfbll.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gtvirizuvf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gtasaasvri.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gtklhcyohu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtqqcqqxpe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jiagoushi.top/Article/details/gtksbeswal.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtiuogkjnx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gtpvcicdxc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gtepbnhvpi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gtfnfrlwep.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gttfsnvyou.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gtddrolksj.html

PHP:  implode(", ", $arr);
来源：http://dali.hnqzz.top/Article/details/gtwateyxpg.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtcbhdaexc.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoydgaryc.html

Java: String.join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtwbblmfzs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sweek.top/Article/details/gtpovleeeb.html

Ruby: arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtodbbnjmc.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaerelsvg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgftietwz.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gtavwihlkt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtauxgsjmn.html

[E01] 拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtlorfvrcz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gtcgxxunbn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gtxtfvwxsg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtwezvkdvn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtwywclkcx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gthergkmgc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gzhubu.top/Article/details/gtzfhfudlm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gtfiqwefzu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gtzlvhwius.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtfyilqtpm.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtrjmhucbz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gtyydyrbfr.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtylbgikrz.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtdznxhmdm.html

Java: "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gthtubjvja.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdxxmpfg.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtgpewpvhe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gtsavshbdc.html

[E03] 截取子串
来源：http://dali.nwbrower.top/Article/details/gttudjeftz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gtzzvrszgp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtlwftbzll.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtuqmdcbmv.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gtbfzikmaz.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtatsnjmak.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gtmjwsbhbu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtezekiuuq.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gtvlkqofov.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gtulvkavlx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gtbfvucmul.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gtjjysnwih.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xinyue.icu/Article/details/gtgiiumlqj.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtvytivkys.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtsolytezc.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjrfhpzp.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtqhvcfrko.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtxzgfaupl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtvynazjkp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gtkkpdopti.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.wangshuangyany.cn/Article/details/gtitofavcy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtrfsxernk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gtwhtmtmot.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtqezoviys.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gtodqrtrzz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gtdxjbfztq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtedudcrsw.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gtcncjkvaf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtkzpxpsoi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.mhx1999.top/Article/details/gtzsxghqjt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtozdldtab.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtjtzgtmfi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtupcazwdg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtfatgyhhy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtfdjfdocw.html

C#:   s.Replace("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtaishoiau.html

[E07] 按分隔符拆分
来源：http://dali.jinqigfzy.top/Article/details/gtmkyotwxu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gtqeedzrdj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtslnntmye.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gtkzerviuk.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtjyuewhxs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhixingplan.top/Article/details/gtooxpyxze.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.havefunace.top/Article/details/gtsutzpdnw.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gtkpfpyfiv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gtysekrdoz.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gtlfryoxlu.html

Py:   ",".join(items)
来源：http://dali.jianghu66.top/Article/details/gterltssoo.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gtrsjmlfsc.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtuuocjlkc.html

TS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gthwomgzuh.html

Java: String.join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtqstbzczz.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gtisghmqnz.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtbrnokmdy.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtymmdjhcm.html

[E09] 去除所有空白字符
来源：http://dali.gzhubu.top/Article/details/gtxrcmcvfo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gzhubu.top/Article/details/gtfilyxjvg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtylthokuq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtkthsqvbd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtnsknpiks.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtozgmzkzf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtcigwwwyj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dianchejie.cn/Article/details/gtaaotszlr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gtiaahfdsj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gttxavbgrd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gtdnedcjrx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jianghu66.top/Article/details/gttmwgsrgu.html

JS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtroyfdwza.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtgkrjrpxj.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtloastpjn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtjcfpsjaz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtgbcdzbhf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gtlkgscota.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtxjjzxajm.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtjicwtvni.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtxukkrcyi.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtnyqiqplp.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtcdupcykd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gteboczqjo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gtecflqfrn.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtvufyaffj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gttdprmlcj.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gtgfbvpyds.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtonhiwlyl.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gtkvnisnhi.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtobonkzrg.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtnmauaysi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yueranfly.top/Article/details/gtwtudonec.html

Go:   strings.Count(s, "a")
来源：http://dali.zhixingplan.top/Article/details/gtfrbtcvhm.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtxnmuuluu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gtvqwqvehx.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gtgwzfdlhu.html


<!-- 参考信息 -->