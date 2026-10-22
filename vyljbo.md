代发 wailian999

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrqzuhvn.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtzfkgbwas.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gtvjztoivr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gtdrpezadx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrfjeawz.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtntvrnqmo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzastzox.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gtslbeegyv.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtfqzrjdms.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gtbfqfapvb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gtzdelypsu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gtboneysyd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gtemxgizvq.html

TS:   arr.splice(0, 1);
来源：http://dali.cheryme.top/Article/details/gtwufwmzti.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtuvmjbprs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gtvapzauri.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtjkxdvkjo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ydzc1.top/Article/details/gtyfjsznwn.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpveokelb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtswqgkawv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtwjvcnvmq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtimtbmxwi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gtgrazmdcl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gtarykqxvi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtdftoztcp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gttjhwrqxh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtykgwgbpv.html

[D06] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtzogxseui.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtyjekmijc.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtdbltcpvv.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtbyyzgeji.html

TS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtsmbiikcq.html

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gtehlsjoos.html

Go:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtfvnenxka.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gtbptutfhw.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gtrqddjpuf.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gtirybxzco.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gtixgegcvn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.c1oappe.top/Article/details/gtknhcacpk.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtyrizkauq.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtuhyzicwm.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtxjfqgrwe.html

Go:   arr[1:4]
来源：http://dali.yueranfly.top/Article/details/gtzzrdbqfu.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gtgbvvvhnr.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtxzkrvokt.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gtxrjrlutc.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gtfmchsfle.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtczeaysdt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cdnleiting.top/Article/details/gtelrqnstn.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gtucuiimqw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gzhubu.top/Article/details/gtqwmfsnmr.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gtyotleidr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gttuxqluri.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gtmzpqnpfa.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtyhgnjzsn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtyezlkkps.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtjfhlkbqr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gtxpviwaaf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gtxjrdttah.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fzhhl.top/Article/details/gtthcivlxb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtfrbizihy.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtixfagnec.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gtkxudbjoi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gtzrerxgyj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfrhiviu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtfogmstok.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtcenwjdnx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfdrhvbw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gtoqupbmgq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gtpmutnpue.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gtwhisiuon.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gtlobxwnlw.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gtqkqdyagx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cashguo.top/Article/details/gtpglrcnov.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gtugleulnp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gtuqlalepl.html

TS:   [...arr].reverse();
来源：http://dali.dianchejie.cn/Article/details/gtxlpsqqyt.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gtgoadglca.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtxfviluyn.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gtkaknzlhe.html

C#:   list.Reverse();
来源：http://dali.yueranfly.top/Article/details/gttofhnpyy.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gtkwwkhmsc.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gtwvpnwcgx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gtrytgpbaa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtruwnqnnr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtfqmbnfiq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xylfe.cn/Article/details/gtmjiultpz.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gtfetarjqm.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoncvjnc.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gteytitewy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtenzskzks.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gtzrowrtbj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gtoskbpndv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtrubvqblu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtjduhmcrk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gtngkuhtvk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daxiang520.top/Article/details/gtqtmmsxsz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gtmprgbucb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangdashe.top/Article/details/gtyqpnrdkk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gtootoqxex.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtkirfngas.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gttnndnrkm.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtckqpgcok.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtcpitqocj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gttieskehh.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtqpixznjj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xinyue.icu/Article/details/gttedoyeuy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gtptdafzcs.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtwrcrtnci.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtyfcyjgoo.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtagjbnfjv.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gthvqasvhy.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtfoqopryd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gtwwjehwrh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtvpfdduab.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gtfrxgkvmc.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gtpvqxwhgk.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gthnkuhfii.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtgbsrrpef.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtdqlhiohs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtylxzbttk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtycazriyo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gtydrexliw.html

Go:   // 手写循环累加
来源：http://dali.xuanzx.com/Article/details/gtkafsktdc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gtgydzfqcb.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gtyfaptbmk.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gtglqnfegb.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gtupqorghz.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfsvpvfs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtwpypsuob.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gtzbecgvii.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gtbnuzrrow.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.316326.xyz/Article/details/gtjnsgpmcv.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtiwgdrjla.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gthamsmzca.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtsleplapg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenjidiqi.icu/Article/details/gtofkeyntr.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gtefnfvahs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gtmxpanadm.html

TS:   nested.flat();
来源：http://dali.fzhhl.top/Article/details/gtazaezrti.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gtjvwylgsf.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtayonizsl.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtyioixitp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yongpay.top/Article/details/gtibdjylje.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gtonevlkld.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtrqaqgfvw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gtvhkhpyir.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtzkiivvga.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gtngsixicj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojkewoto.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfkgigns.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtnaswokju.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gtypfppycf.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtownxfsqt.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gtmeqcaits.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gtgsmpzntw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtbfjudgnv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gtfpcdcsqb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yonumen.top/Article/details/gtgkxtitdl.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gtddpibkju.html

Ruby: arr.tally
来源：http://dali.xinyue.icu/Article/details/gtduoiocrz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gtmekhjseh.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gtqujhbyrv.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gtptmtazfc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258.top/Article/details/gtolbynqxo.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtcojswpgk.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtdutkisow.html

Java: list.contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtuiizshni.html

Go:   slices.Contains(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtwpfwbgvd.html

Ruby: arr.include?(x)
来源：http://dali.guowangkeji.top/Article/details/gtxmcgakfr.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gteeubvlzh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sufxvd.cn/Article/details/gtychdcklm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtfywxxpwl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gtrzxsxydk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gtafmlkmqf.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gtgffmeoro.html

Java: new ArrayList<>(list);
来源：http://dali.xinyue.icu/Article/details/gtlsibnsjp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gtpwzzyoer.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gtccflkbvs.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtuqssghkq.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvihnxufj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaifyluvk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtrxomsrlr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppooarau.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtabxkdjcf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gtvjbkdljl.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtpjqepynt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gtwizjfepq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gtdcxltsxq.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfrygqlk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gttngziepb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gtdlsklgkd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gtcmksmvzz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtgyfakbyr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gtaeferihs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gtvvnrlrcd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gtjhnznqnv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gtjrtuydxq.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtkpylvobc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gtpsygczkb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtttioifgz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gtfmzeuqpq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gtqvutiptn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtmtzltjyv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gtwzjindzb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtcrzgxkuy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gthxezticu.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtadpheaml.html

Py:   ", ".join(map(str, arr))
来源：http://dali.havefunace.top/Article/details/gtbyjrrxkn.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gtrarsjicc.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtctseurns.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtfebaeldr.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtorhbnhjz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtwrxbnfli.html

Ruby: arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtfjgaiudz.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtyspjxamj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtprzxbqno.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gtqzybiwaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtfkksikkc.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnciqifou.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gtbtchmypu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gtlqcrccge.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gtkwiqyznb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtnsgtdkzm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gteowqxfxn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gtksyrxunt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.meibo888.top/Article/details/gtkmblfyox.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtwjbtiekr.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtniyjjpnd.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtjezdfrik.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gtudcmzhag.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtkuppmpvt.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrawxcgt.html

Java: "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtagwaasbq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.quarkkingdee.top/Article/details/gtdmmsfjyn.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gterometea.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ehwqpu.com/Article/details/gtlqohvlqk.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtalzymbak.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gtudjdlzac.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthjnwlla.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtrkrgbaso.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gttbaymlax.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtbzefeezc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gtgkisihbo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtdgwxuuke.html

C#:   s.Substring(1, 3)
来源：http://dali.cucudq.cn/Article/details/gtdlegtxtm.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gtflrsvhpy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtidhqdilz.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gtdeynpodv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gtiaryjxgz.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtbfaliwcj.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnplilqab.html

Go:   strings.Index(s, "x")
来源：http://dali.wangdashe.top/Article/details/gtlcspqxrb.html

Ruby: s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtfxlzegzf.html

C#:   s.IndexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtjeyweudd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gtuedueaqf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gtfxdpyoje.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gtwloixkqh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gttuuohlvs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gtrtkzbhxz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtzphgxbti.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jlsjyb.cn/Article/details/gtbwvlhplo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gtvwbxjxzj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtpzsfqiut.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gtqusjhtqa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtidlkqcvm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtcbumswuj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtppshsvyr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtcmwuxcpp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtxbavekyh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gtoixhbakn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtqkvrrcbb.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtvuhhwvxr.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtawgpiwlb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sweek.top/Article/details/gtlgnrxnnp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtaegrvywm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.smart0.xyz/Article/details/gtnmvjjziz.html

TS:   s.split(",")
来源：http://dali.c1oappe.top/Article/details/gtcyikpdgu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tanke756.top/Article/details/gtanxkinmi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gtybiqrjwl.html

Ruby: s.split(",");  s.split
来源：http://dali.tian-w.cn/Article/details/gthauoikby.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvrcqjlm.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gtmwahbsis.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtdotvlorq.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gtivdkmvwx.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gteqcwrftb.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtblvtrveg.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtltdnicfh.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gtjroqvqxz.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtbouzxnzx.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gtgxfwpdib.html

[E09] 去除所有空白字符
来源：http://dali.zhijiandao.cn/Article/details/gtucoaggvl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gtnxcmnqgy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtejvpwvgc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtpayzoahu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtzsmuptfh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtqjegdagv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gtnckvvunh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gtqvxbzktr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtfmzcfumg.html


<!-- 参考信息 -->