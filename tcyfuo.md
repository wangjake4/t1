代发 wailian999

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2borhkzoq.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2wcdgzasl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhpamkxs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2nypkpsoj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.kuanghao11.cn/Article/details/gt2jzgxzmbt.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gt2piqmospm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gt2oafuexqw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gt2zcgvnjkn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gt2yyfsimxf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gt2gmupkzcc.html

[D05] 访问与修改元素
来源：http://dali.9152youxi.cn/Article/details/gt2tocbhgge.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfzqqozt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2xzzspfuw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gt2jxbfbhxq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigfzy.top/Article/details/gt2vsxwdklu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gt2phlusepk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2dmzntqat.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gt2kzzczskr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2tgvigqxz.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gt2maimuxus.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dayesxel.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gt2byhxafyf.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gt2zmuipidx.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gt2dnjvbyec.html

Java: list.size();
来源：http://dali.yj20258.top/Article/details/gt2occibwsv.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gt2agoyorbb.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gt2rwxwytrq.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gt2vpylggxh.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gt2kzwtlphp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqotrtuw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxinkj.top/Article/details/gt2ldlhdoxt.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2ztabdhzl.html

TS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2dvvcijkv.html

Java: list.subList(1, 4);
来源：http://dali.havefunace.top/Article/details/gt2ypiewqmf.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gt2jnkgwmdf.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gt2gfwgqjdo.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gt2cfqrgwhd.html

[D08] 合并两个数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmvpotlc.html

Py:   a + b;  a.extend(b)
来源：http://dali.yvedp.cn/Article/details/gt2ccrbewgd.html

PHP:  array_merge($a, $b);
来源：http://dali.shzxlz.cn/Article/details/gt2gcskhpqu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gt2lesrjpqs.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gt2nlttzubt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gt2anxbnyew.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gt2zuebybbu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gt2omqxgolw.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2vmqnwjee.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gt2gxhtlktg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gt2glbojwms.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gt2smbrtdmm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gt2rsangodq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gt2fongelek.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cdnleiting.top/Article/details/gt2ituafoiy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nghbtdaw.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebmlgugo.html

C#:   list.Sort();
来源：http://dali.zhengqikj.top/Article/details/gt2eczlhifs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gt2hieapohk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgkuqlgk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gt2fgkhtczl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gt2arrbjbxq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbamdciy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ppjwa.cn/Article/details/gt2qipzckto.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gt2kgqhumua.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258888.top/Article/details/gt2cnbxyhtz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gt2szjwrwgg.html

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gt2fwrctiwx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gt2tgmoiphl.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2yipfugxq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gt2mhrirriy.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqbtdtao.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gt2eslchvbn.html

Go:   slices.Reverse(arr)
来源：http://dali.redwolf501.top/Article/details/gt2nydqgkms.html

Ruby: arr.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2zxvowccz.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2nnyiepbm.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gt2fmgjijgs.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gt2aleaqbwq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2pnaixqhh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2ofeazvoa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gt2xxubfjom.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gt2lriigzsm.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2ymmfgoof.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gt2tphlbdsg.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gt2crxauaqs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gt2erjlhmch.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.andypj.xyz/Article/details/gt2wmqhflsd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gt2lngmysdr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2pbmaybaw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gt2rfjtakya.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2wntlvely.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gt2jpfrlhcw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gt2gniekmbf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crvruiwv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gt2ojijscgj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gt2tvigvhay.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tian-w.cn/Article/details/gt2ntauwosz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqeidui.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gt2wtdjykcp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2shqenrza.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2umlmosml.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2dxqodndo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyvzvllt.html

[D15] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2codaqqll.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gt2jswgqcrh.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gt2nvbfmjui.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gt2mbmddlgx.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gt2quceqxpa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gt2pyojjnno.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmanngml.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gt2nzgrfpxn.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gt2owyolykq.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gt2vfqiwcpv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2fnvvdwtj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2kpclnzrx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2jodrhozj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2freprowp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gt2kkcaxajj.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gt2upcfmtnk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ehwqpu.com/Article/details/gt2zrodftqj.html

C#:   list.Sum();  list.Average()
来源：http://dali.jlsjyb.cn/Article/details/gt2pgulyzrn.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpqxdjed.html

Py:   max(arr);  min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2hyccwnra.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gt2wekzkbku.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gt2sxwonxbh.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2dlzqswws.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigufen.top/Article/details/gt2ujmlgdxd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gt2mkpetton.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofxmyqdg.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gt2epseprpa.html

[D18] 扁平化嵌套数组
来源：http://dali.pycfn.com/Article/details/gt2cezeaopq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evmfevqm.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gt2eagurikk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gt2kvaloofy.html

TS:   nested.flat();
来源：http://dali.havefunace.top/Article/details/gt2mitqmesj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shuidangran.top/Article/details/gt2qbddrvpu.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2frxxdbog.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gt2rkxndobf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2ytiydfua.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gt2dvxvyrcj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gt2rvdfbbqv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjpotupk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gt2sqcaiafa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gt2bfkstzzs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqznfayg.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gt2nsynvccf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gt2mcekopko.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gt2islmtoww.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gt2qqzlyfdn.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqqpbrfa.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2fbkzienq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gt2gdrxnfll.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2jbyqclln.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gt2chvzlkyp.html

Go:   // 手写 map[T]int
来源：http://dali.daria6918.cn/Article/details/gt2qxtcrepv.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gt2ypdjoanb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gt2ekmytgwl.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gt2dvnnsxak.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gt2jzbzyyns.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gt2ogftrgie.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2wrbzmrkg.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyksdtgj.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gt2hvszxuux.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2mmgvzhcb.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gt2kwxtkqeq.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvqveflq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aobydaob.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odcismbm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gt2uetzfdib.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gt2oahpajxn.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gt2mdzstgfd.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2shoquhnx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ydzc1.top/Article/details/gt2zsdlrsib.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrcqaqye.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gt2qjjhrapx.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gt2qkszwxvw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gt2spnbfssq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yvedp.cn/Article/details/gt2wdrucyuq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2htnarots.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gt2toddgbaz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gt2ugotaqij.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gt2hkypflrz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gt2chusngbc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2hjnqfmvu.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gt2ggwblcvl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aizwys.cn/Article/details/gt2twthvoyx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gt2xbpgauzt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gt2qlycoefw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2lczrspjh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gt2pwbilbax.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gt2wijoyjhg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xziqi.cn/Article/details/gt2xkhkdjmz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gt2yjpowhli.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gt2bchwfwor.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gt2thwrytqx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gt2jsflqtlc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gt2xwhjcdue.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gt2lwldxetk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2lyaabbie.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gt2iutexusu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gt2uuyxyvpl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gt2fhmfwvua.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gt2gcafsxha.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gt2xjpufgwk.html

PHP:  implode(", ", $arr);
来源：http://dali.nwbrower.top/Article/details/gt2fbkrdpca.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2oamwmahn.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmoukds.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gt2putzlsdu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2armnwrza.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgisfmjx.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gt2saqesvhb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2elhetalz.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gt2pqtsmoqf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2gwtxyvsd.html

[E01] 拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gt2jqssrjgl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gt2pwdftwdt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gt2yrihqpib.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gt2jfokrtsg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2ruzvuzjz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2azpttwww.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuxming.cn/Article/details/gt2ksymsnkz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gt2eekliftq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2mgvcptdi.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gt2xqfykxue.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gt2hfzgbddm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tian-w.cn/Article/details/gt2hkaqbohz.html

JS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2lilyjfbr.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2czezkxlm.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2anqfowuy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gt2wnuzjapx.html

Ruby: "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gt2foiymoky.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuxming.cn/Article/details/gt2kvbzngis.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gt2ckhptown.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gt2wrjmnuoz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2horfcjnk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2vwolnbzc.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2fwnwwkcw.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2cfzryimz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.mhx1999.top/Article/details/gt2tzdkkuit.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gt2szoxgtmo.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2xhbnnfro.html

[E04] 查找子串位置
来源：http://dali.nanxinkj.top/Article/details/gt2cixlccsp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2bfwrjlxl.html

PHP:  strpos($s, "x");
来源：http://dali.andypj.xyz/Article/details/gt2cakambgg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.mhx1999.top/Article/details/gt2ljtqbuno.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gt2wnkrwerh.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2hdfhcyfc.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gt2aygzfzuk.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gt2xoyxkckt.html

C#:   s.IndexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gt2rsbjsrtd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vueuefyp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2eheceeui.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gt2ebyxoyhy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2faeamxox.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfdnwoox.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2ceswqyem.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gt2bqyxxyky.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cheryme.top/Article/details/gt2yseyhbwf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gt2falhgztk.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtolrdbv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gt2rddrjwkt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gt2dkzaaxri.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2lrmaycrd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gt2sqrfejkw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2lqmwqqcz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gt2fxfhnolu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2yvwlumgf.html

C#:   s.Replace("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2odupphfq.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gt2trftvmwa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gt2xrtvqbap.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2blzrpdkm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gt2qtwebkzt.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gt2gdltodcg.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gt2zrvpwnph.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ztqshlcv.html

Ruby: s.split(",");  s.split
来源：http://dali.redwolf501.top/Article/details/gt2leejbjel.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gt2xemxaocy.html

[E08] 数组按分隔符合并
来源：http://dali.nanxinkj.top/Article/details/gt2zvlwleiu.html

Py:   ",".join(items)
来源：http://dali.sufxvd.cn/Article/details/gt2dizwmeha.html

PHP:  implode(",", $items);
来源：http://dali.quarkkingdee.top/Article/details/gt2reyoclsw.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2jwafnlxx.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2fpindydu.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gt2zzbzqsdx.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gt2kczvtvbf.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gt2wjjrzdhz.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gt2htwzxbsi.html

[E09] 去除所有空白字符
来源：http://dali.yuanzhike.top/Article/details/gt2fdviohfd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gt2vosawsrn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zycfv.cn/Article/details/gt2zlzjrdjg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gt2ngorwelv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2tpfphlrw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2cqvofhmr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yonumen.top/Article/details/gt2lrespghq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gt2tcrssavh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jianghu66.top/Article/details/gt2cffqjhpv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gt2bsgbpuow.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2vgbduzrd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gt2prqvsmdc.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2jsbsekef.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2eiacsnay.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2hakvrtfr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gt2wpwwdtbg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgqczvdj.html


<!-- 参考信息 -->