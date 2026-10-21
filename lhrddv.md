代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daria6918.cn/Article/details/gtymsbpyer.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gthvrygfrz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guowangkeji.top/Article/details/gtnckbpmuo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gtmoxhmdxt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gtnykylumx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtinxuzifu.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gttrqalmqq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtgxaphitj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtxudclzcp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtctpxfwdt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gtdnfxfjff.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtzqikijno.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtbqwodyms.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtxjegfhkr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtjkciszpn.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtdwffsltl.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtwdtxeruv.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtrqsfaqto.html

JS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtcaehudhn.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtdxaspyhd.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gtbawcojmf.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtgtzkrpnb.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gturndyrzo.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtpvfzjjjo.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtgsnjkvwk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gttvrrkvqh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscjodtwk.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtvezwjvfo.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtrijdxzid.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtyquljolp.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gtldnxpada.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtkvyspuzx.html

C#:   list.GetRange(1, 3);
来源：http://dali.fengsongda.top/Article/details/gtudgsqtla.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gtjzrgyepx.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gthnavckyv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhengqikj.top/Article/details/gtnyxddxga.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdsiieqw.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtrizolrit.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtwskkclks.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gtdupedfnh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gtvijhstoz.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtjxiqnllm.html

[D09] 排序（升序）
来源：http://dali.feifeiyinyue.top/Article/details/gtoxsrtaey.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtvwfldoln.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtkneducrj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigufen.top/Article/details/gtfthpbbkh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hongshengwenyu.top/Article/details/gtboptmmhp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtuezawuar.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtglvaqywg.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtzeexmfdy.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gtzzlrduao.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gtubgekkpo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtqdxlnfso.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtvbkqglxo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtbfswbkxs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtyyzcwiml.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258888.top/Article/details/gtwpmllqjg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtxmtohimm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gtjoscnwqw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gtmyjhwfsm.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtnrijgwax.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gtatsiaupc.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gtlhvrupee.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gtfdjzrhlc.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gtgnmrdpmh.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gtorlhevzb.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gtqbmkukzi.html

Ruby: arr.reverse
来源：http://dali.sxryk.cn/Article/details/gtzkxsrrjp.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gtvkpihhyo.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gtvqeqjxmo.html

Py:   arr.index(x);  x in arr
来源：http://dali.birdmap.top/Article/details/gtqiqzpzbn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gtptychxlq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtynxfghey.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtmiboxxcr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xziqi.cn/Article/details/gtkcuvafmg.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gtwfmnutls.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gtbiisnqby.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtqemszwot.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtkplfnehb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtsqosynym.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gtfukzzrtu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gthxydpcbw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtzdavbpcs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gtgbhoeskj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtjaammpdh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gtiteuiqpu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtqolqtwcj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gtbidtghhi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtkknecybs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtbewdgzvg.html

JS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtjrpqdlqr.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtqvnsmhjw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gtrxkjpqed.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtmsgsnupq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258.top/Article/details/gtikiegbyy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtqnqradtn.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gtfwrpqjhp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtcxlggwtb.html

PHP:  array_unique($arr);
来源：http://dali.xziqi.cn/Article/details/gtmibrupea.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtvrttkjey.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtcpwirdpc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gtkodymgtn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tianlin.xyz/Article/details/gtrywhyles.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gtbwtrrnww.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtjbdhjdgg.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gtzweehatt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtpaaovsbh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtphpsdqgw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtdzqvehdz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtsmsvjtvd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gtkbebzhqx.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gtemiobdzh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtisvgtsgc.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gtbmhtekck.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtsresfhey.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwbugqpc.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gtwbvqadji.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtfpzxtvyw.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtinsjzjlr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxovvvgx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtctekzfyk.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gtbwzrcbid.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gtaurowsnu.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gtaoqowiga.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pengpengdd.cyou/Article/details/gtoysmptou.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gtrbzonoke.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gtimzhbile.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtlthujezk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gtqddmxvkt.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gttfniktvw.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gtbqfbagxo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwhrjzxl.html

[D19] 按字段分组
来源：http://dali.ehwqpu.com/Article/details/gtvpjynpwc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gtynuajsxe.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtoblihugl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gtoncppuyb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtecntqfse.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtnsdwsuhf.html

Go:   // 手写 map[string][]T
来源：http://dali.chenzaomai.com/Article/details/gtyoeexjsa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gtlqipzkhf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gtdulvrowz.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gtfhxweyqq.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtnciigayg.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gtemfxyzcu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtuynbxiud.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtwlgmwaek.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gttwuiirms.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxqkkmho.html

Ruby: arr.tally
来源：http://dali.birdmap.top/Article/details/gtlgfnnsci.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gtbtycnota.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gtdzqbrasx.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gthkksazkr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtysgtzqad.html

JS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxlyofuc.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtbfkmewgx.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtrzzztttj.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtwzswhuhs.html

Ruby: arr.include?(x)
来源：http://dali.tian-w.cn/Article/details/gtigyqncgu.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktnwqiby.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gtyufijdga.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtjxcttxoo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtymrqczqk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gtsyfkplcc.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gtfzhxidpc.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gtrkpzdspr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunmxvpqf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gtroftusli.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtqfxuqyyi.html

[D23] reduce 累积计算
来源：http://dali.wangshuangyany.cn/Article/details/gtgsamlzqr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtdbjavpbj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sysykeji.top/Article/details/gtewwljztw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtsrpsfjaa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtkclhedec.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gtdxgvuuoo.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxwzlraq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gtltcotklg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtgqagwyzu.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtsmsrlalm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gtyzisihvi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gtshycdfvs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.mhx1999.top/Article/details/gtlxaawbor.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtmzugiyed.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ybcxt.top/Article/details/gtzgosyhjl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hfpthk.cn/Article/details/gtwxmayrsn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtolawmhjp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.haohaochexian.top/Article/details/gtyyxlfaqs.html

[D25] Set 集合去重与交并差
来源：http://dali.c1oappe.top/Article/details/gthnfmnnee.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwtzkubo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gtmyuhlwox.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtldjgfsoe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtjplarbik.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfncusgy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gtddwholyj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtfporqnji.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtzusoksma.html

[D26] 数组转字符串
来源：http://dali.xziqi.cn/Article/details/gtzczxhxpn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtlrmaptao.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtyymacpay.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtnndpaoew.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtgeqdzccv.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gttcoowoco.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gtxsroxary.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtqkxzdlvn.html

C#:   string.Join(", ", list)
来源：http://dali.shangyingyoupin.top/Article/details/gtxezwbnmn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgbmavisi.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gttsgujtff.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmemlmrix.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtgghloehf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gtadcsmuhk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gtdxqbghnq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtaxeboppn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtwcqgylnp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gtecohhdha.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gtpvmvrrxj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdksxleay.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjfkxbvu.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gtvghyagpb.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtghkhtbyu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gtbvbzfiyd.html

JS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtqigmokbo.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtrmjxkbxn.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtsxwchmvv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gtvlspkwyk.html

Ruby: "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gthxrxtbth.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gtmizpfups.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtdckdrxvb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gtifybmmhx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtgswaxhlm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtxhlscpep.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtttujvkvi.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gthbgxrlrc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.mhx1999.top/Article/details/gtflfmccff.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj202588.top/Article/details/gtzbuiwekt.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gtfzzjxuzr.html

[E04] 查找子串位置
来源：http://dali.jinqigfzy.top/Article/details/gtocuwugys.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtxyyqvdhw.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gtukdduibt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.9152youxi.cn/Article/details/gtoyevzvpf.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtmlmpiceu.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtwbijobet.html

Go:   strings.Index(s, "x")
来源：http://dali.ivvv.top/Article/details/gtigjebiqx.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtdjteetxv.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtgeiyfzww.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gtklxdzabw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigfzy.top/Article/details/gtmepmyxal.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjsfcjop.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtqkfrwddd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtrfsnebcf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtdradowxi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gaohongyu789.top/Article/details/gtwrowgxge.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gtorutjumn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtzybjacis.html

[E06] 替换子串
来源：http://dali.zdqjudy.top/Article/details/gtjsgvumin.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtthkyulnx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gtfqovlykr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtrveefwuh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtsdoclsov.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtdzzbnicw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jyoumei.cn/Article/details/gtkdqcsmwy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtowcfksfu.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtxfburhlv.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gtkbwfuani.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtpirpevfn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtwmhnuvvh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtinskbyrl.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gtfgivgxcw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gtjhotbqsj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gteumdeeyo.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gtmhwmgsfc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtcwkttrww.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gtaggokqly.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gtmmqbhpwv.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gterublhve.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtkmaadcxt.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtfvzjplno.html

Java: String.join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtajntrrsj.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gtlhjsbmqz.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtfdzcwtap.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtfuvhrqsn.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gtquznohqc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gtbdzlytwm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtvfpowraj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtkoufqloi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrcuknxw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtgunccicp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gtyywemfsd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shuidangran.top/Article/details/gtayapxfvt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtspunsrtl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.0kj1m.cn/Article/details/gtzaojtlqo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtlztmzzbl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtabhgkpnd.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtnokwizmr.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtstpduawa.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtceimlrio.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gttpijjuvv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gttaagotyh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gtdknrepne.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gtiybxtlrm.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtchaoeoqm.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtyzdveljj.html


<!-- 参考信息 -->