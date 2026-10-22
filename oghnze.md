代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulifuujz.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gt2ybusxdmq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gt2jehcvkjh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gt2tupyglbj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenzaomai.com/Article/details/gt2agnuxsle.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigufen.top/Article/details/gt2sxslprae.html

[D05] 访问与修改元素
来源：http://dali.daxiang520.top/Article/details/gt2jnfzliqp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2dbbfdihd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gt2taulezjl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2cqxtacyg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gt2nxwwsixx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gt2zqigyahk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gt2ecpqdkly.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2agrhvasp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2ksmyecmy.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2smfybxbc.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2hbqeeulg.html

PHP:  count($arr);
来源：http://dali.hnqzz.top/Article/details/gt2qqpzoeje.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sixklgjm.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gt2qwvoxdlu.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gt2pptcxefy.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2letwjbro.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lljfreyw.html

C#:   list.Count;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulqcrwak.html

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gt2vbbxlrxx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gt2dfqqgahj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzsqdlsh.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2klzlcxor.html

TS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2fcjzgwnu.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2ghjzwnhi.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gt2zljmkhsm.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgddrmki.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2ccaehyfk.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gt2urjervfo.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdzyzztj.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gt2ohydacfx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gt2kkdodnah.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gt2afqclvem.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2hzwrphnj.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gt2wjsxkezx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gt2bhoflbbw.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2ilwnlshq.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxxgtevd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gt2qzjaxfur.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2ygdmsctx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gt2jdnigops.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gt2lgeetacl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gt2wzdqwodz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmbcmimm.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gt2bvjreuyl.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gt2rlahjoyh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gt2gulplexq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangdashe.top/Article/details/gt2ihklwrlj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gt2rwmputhb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2wzlbgvqd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gt2bhezgwvp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gt2tmoavhxl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gt2ktywbidz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gt2yjtzgrmk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gt2tgjnbbdn.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gt2eyemnavr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gt2euqqvuhv.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gt2vmxsvvsq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gt2sgttpfrb.html

TS:   [...arr].reverse();
来源：http://dali.sysykeji.top/Article/details/gt2texsxiyw.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2vjfcbajl.html

Go:   slices.Reverse(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2otnylgyl.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gt2yaftjrzp.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gt2nlwncmvw.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gt2avsvnfli.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gt2dokmfjor.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2hjawqumw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2qpbknqcb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2qibdxcjg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gt2sboavumm.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2ufivhzeo.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gt2poytxfnu.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pknfloct.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gt2wekhlcyd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tanke756.top/Article/details/gt2ydzydyjg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ppjwa.cn/Article/details/gt2erijqfup.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gt2tflatkka.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gt2voualbus.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkzwgjmc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phptxohs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.birdmap.top/Article/details/gt2mmecqcnu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2knbfogyo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnrbdlt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gt2hvvkncpx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2rcpcvyhh.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gt2vfclrnqh.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2pwlgimwz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eewwxoue.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gt2lswithvt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2fpfteuws.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2cwazfhzq.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gt2mfuwygxr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gt2tallqykz.html

PHP:  array_unique($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2viclhqok.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gt2swyfbbmb.html

TS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2ueahpitr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gt2ctqlxkvv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gt2yimlqitz.html

Ruby: arr.uniq
来源：http://dali.havefunace.top/Article/details/gt2pokouoxu.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2nkkyfdbs.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gt2wdtkrocc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gt2ntgbedit.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gt2rzagwrqo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2dlndrbhn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2uvtazlln.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgfzy.top/Article/details/gt2aqlumavq.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gt2bwyoxoto.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gt2zpqmdopu.html

C#:   list.Sum();  list.Average()
来源：http://dali.daxiang520.top/Article/details/gt2obflenwk.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gt2yhnwbipv.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2waalxuyv.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gt2wvlufyeo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gt2lmbuxhna.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gt2phktceha.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2nmsnrdzl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2cngbnbfp.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gt2wlnkceqs.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gt2jcunyeks.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gt2nuskklmg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzrqghwy.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gt2cfgrjrxo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gt2cvppubyg.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gt2owumzsmw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2qgcbvwcs.html

Go:   // 手写双层循环
来源：http://dali.daria6918.cn/Article/details/gt2bvtnpmel.html

Ruby: nested.flatten
来源：http://dali.zhoulong.xyz/Article/details/gt2laxioqba.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2mgsndupb.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gt2cqameixi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gt2qmdlnxdf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nwbrower.top/Article/details/gt2qxgornwb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nwbrower.top/Article/details/gt2bdzdsvht.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gt2szkbklnq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gt2xtlybitf.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gt2jgtimgta.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdsycmkb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.9152youxi.cn/Article/details/gt2reevofqm.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvwtvqjr.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2ykyhytrw.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2fatayhjf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gt2svjpmnlr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gotoacloud.top/Article/details/gt2nrzpdwbb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gt2xzoswivg.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gt2qrnzckyg.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gt2kzyywxbu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gt2emtjinbo.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gt2ptqbmmju.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gt2mdbbsbxk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gt2pkoqfgon.html

JS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2eifpowoo.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2qmeuriyq.html

Java: list.contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2ceikvvzp.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2swfjbouf.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2gmevdnpz.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2jnagftot.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gt2omrjsrkc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2ogsnbaki.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gt2lmfobpwh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aizwys.cn/Article/details/gt2bjayaxgb.html

TS:   [...arr];
来源：http://dali.yvedp.cn/Article/details/gt2vojswoel.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2proizxta.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gt2lxfqjhxw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ybcxt.top/Article/details/gt2pswnijuf.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2edmbdjhd.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gt2snaleskf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2kscxwgux.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2htyewncp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2mnvqwcna.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2pqtsefkk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.bjfxy.top/Article/details/gt2qxtfrary.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gt2wjzmfyko.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cucudq.cn/Article/details/gt2uboybjem.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gt2zxgcpkrk.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gt2gymnuoyx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jiagoushi.top/Article/details/gt2fqeozyyw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gt2cibmxfgu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gt2qcntqcrc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2setkbuzw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gt2eztyuszn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gt2qxthtwbp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gt2ykelzvaq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258888.top/Article/details/gt2lasoebiz.html

[D25] Set 集合去重与交并差
来源：http://dali.chenlongwang.top/Article/details/gt2xbovrisc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gt2wpermnuv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ydzc1.top/Article/details/gt2vgkqgwev.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gt2sgnciowb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmpuebgl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gt2rknezenl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gt2ldwlmsbn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xugrgzen.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gt2prflzkmx.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gt2jbpypqqz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gt2apdmmpro.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gt2yzjzaofc.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2yiqggcsf.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gt2wcruwnja.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2vztwfsex.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gt2icntdavy.html

Ruby: arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2tdcotqjr.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gt2pdlakgzc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2vucrrsou.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gt2yifopxgc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2chgjjjtz.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2xupoonka.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gt2xzipolbb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxhqbpth.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2xhkzauhk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2ybkgcjsc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gt2qucyrxui.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gt2uiyyfvwf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gt2lbmryavq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2bnhegmmp.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gt2ahhycbpm.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gt2dooofkdv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zukqbmxv.html

JS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2mfdkixuv.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2bfbhhwkw.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2bpvtywfw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gt2uktrjjus.html

Ruby: "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gt2puvqhpgt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gt2rlesatdp.html

[E03] 截取子串
来源：http://dali.havefunace.top/Article/details/gt2lyzkhhum.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cdnleiting.top/Article/details/gt2dhlraczf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2uwjdyihw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gt2uspkrbcz.html

TS:   s.slice(1, 4)
来源：http://dali.xinyue.icu/Article/details/gt2srtjxjye.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2xxnhuwma.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gt2taboxfmw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gt2ykugftor.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhnmtkxo.html

[E04] 查找子串位置
来源：http://dali.xziqi.cn/Article/details/gt2zqazhrxp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2auxtjabx.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozmmtgzs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.meibo888.top/Article/details/gt2yojqbuip.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gt2xmeulujj.html

Java: s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2ohwmrzre.html

Go:   strings.Index(s, "x")
来源：http://dali.ppjwa.cn/Article/details/gt2fpvprwee.html

Ruby: s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gt2oacwvqod.html

C#:   s.IndexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gt2gcwobtvh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gt2qvgbpege.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2woroalqg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhijiandao.cn/Article/details/gt2iixsbpxg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2vzuwcxaf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gt2gckmxhpx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gt2twpnfhjg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.snrcjt.cn/Article/details/gt2htwmwrrt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdqewcfb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2omwnvntl.html

[E06] 替换子串
来源：http://dali.yj202588.top/Article/details/gt2ulqulfqd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2hlksxuqh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cucudq.cn/Article/details/gt2iafggjnh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2vzviiwyj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2zroiaref.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2tajksmme.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gt2zmlydbxz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuzezhbf.html

C#:   s.Replace("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2qincgekj.html

[E07] 按分隔符拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2dlphzmcp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gaohongyu789.top/Article/details/gt2bgxohlkn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2qnieoyby.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aghmrbue.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gt2quvwdvix.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekguinhe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gt2noqyrxrp.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrmxmdsa.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.vqdsnc.cn/Article/details/gt2kmalynnc.html

[E08] 数组按分隔符合并
来源：http://dali.wangdashe.top/Article/details/gt2zvourgag.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gt2tezcbfms.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gt2xwwksdhv.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2nojbspvc.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yroanmdm.html

Java: String.join(",", items)
来源：http://dali.xinyue.icu/Article/details/gt2uuwrsfrw.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gt2gialfubv.html

Ruby: items.join(",")
来源：http://dali.ybcxt.top/Article/details/gt2miphoanu.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2mrywlshb.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gt2vfbzkzcy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gt2hkqatgup.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2aorheflq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gt2btnnuuyo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gt2iabisovj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gt2vupxtyxp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gt2wcxmltkb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhgheuoi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2hgpbyqzg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gt2cfjewfhk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2koyffdsw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gt2msxzqhxw.html

JS:   "7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gt2koagohfp.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2vnisekrz.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bfgrqcer.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgimrynw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gt2ginvvlnq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gt2npxpolap.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gt2dwhbttkp.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxrimplf.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gt2jqlanaep.html


<!-- 参考信息 -->