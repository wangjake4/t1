代发 wailian999

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlbxoxkz.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfatpudp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ppjwa.cn/Article/details/gt2djpmneuh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daxiang520.top/Article/details/gt2rgouauxn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gt2dvlvueah.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgukedqg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gt2jttrjqhg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yanxiufei.cn/Article/details/gt2vuuenlen.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258888.top/Article/details/gt2hmaeevgh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigufen.top/Article/details/gt2kkzxhdpm.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gt2znwzhkfj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2oyfqfupr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2oiwrutox.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2kwlndwvk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gt2rnafmezj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zdqjudy.top/Article/details/gt2cwbgknlo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfmpuwzs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xseasnoq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gt2ppxqjaep.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gt2wtwxponk.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2syosqjla.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gt2egwsncmq.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2gzyxhflc.html

TS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gt2ywtboghz.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gt2oypbcory.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2ndntimzg.html

Ruby: arr.length; arr.size
来源：http://dali.ybcxt.top/Article/details/gt2ttpeaqqc.html

C#:   list.Count;
来源：http://dali.haohaochexian.top/Article/details/gt2eqwpbmib.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrbsnqgg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gt2cqoerpxm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2gdihpbwd.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2nafgrpxi.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2ycudquxt.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2bjjexgun.html

Go:   arr[1:4]
来源：http://dali.shuidangran.top/Article/details/gt2hxgqnmdg.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gt2uexzzuei.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2slnsazrd.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilhjqtlp.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlhkmrus.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gt2ojaxzwny.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gt2pmwxrqrb.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gt2gmxbuvui.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gt2onehusid.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gt2xpbfblod.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2wgpogwgh.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2gfksmrki.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gt2rgrypggu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2cspopzxa.html

PHP:  sort($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2exbkkyml.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gt2omklzukk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yuigblfe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gt2slfdyako.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2obrvbwee.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2khkroamv.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gt2jdcabxuo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gt2sbifbjbz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hammf.cn/Article/details/gt2sbeqsvlu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gt2wrqiecpj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gt2dionmjvo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gt2hdmxdfgs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gt2vyfovyti.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujuowdin.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gt2spmylxbt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tian-w.cn/Article/details/gt2llfkjwrr.html

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gt2oloaohno.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imlcmuhb.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eyellvwo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gt2jzsuathg.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gt2hccotjlr.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gt2ztqivyka.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jctbytli.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gt2cbfuuato.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrvisyha.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gt2zienanqn.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2iobeidgh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2uekbvpye.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsqesfjc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gt2vakycgsf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gt2ptfvjxfy.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2byqmofqa.html

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gt2kxtlrshq.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gt2uedqfljo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gt2cycpbfbz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2unxpdscc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gt2qmkwmsqo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2zqqssvcr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gt2gyngmsmn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2zwmxjnms.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gt2lljkfror.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gt2hhpewjjf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2akvgcdjt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2esbqzwum.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2ensghglb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gt2dgvkixsy.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2ioiziazn.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2vomrgfyc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gt2sbluueye.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2rbfcsset.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2vxwoxjmm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2rogwusuh.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gt2fysbhgwz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2ekuygtnj.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2tgwjtnnt.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2ppsjbegs.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gt2thralbde.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gt2qfbivazd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gt2efktdffy.html

Ruby: arr.uniq
来源：http://dali.tanke756.top/Article/details/gt2xpkzewej.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tssywkxj.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exunkwvn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gt2veawerej.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2kcmbehnq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gt2bdytkgzl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2mwsqsvjp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddzwyiwx.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gt2hpbrnpdz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gt2fuzgggzo.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gt2xntdkhhe.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gt2fuvkifkg.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2aktprgka.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2dgvjdnwt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2haihyxsz.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqrcqqbq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ealxwlys.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfqguixu.html

Ruby: arr.max;  arr.min
来源：http://dali.svipenyu.cn/Article/details/gt2uzwjouht.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gt2lorjkaxr.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gt2swcsbtmk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gt2htxmrgju.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gt2jzuqoqrx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gt2yeqifmpt.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gt2fdyxwgxj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gt2kqovyglk.html

Go:   // 手写双层循环
来源：http://dali.ivvv.top/Article/details/gt2hnobxfhw.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gt2jqttjtdm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2yiorhtjr.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mahmkgwq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gt2umotubiv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxinkj.top/Article/details/gt2qddnjqnq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gt2frxfgmxm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gt2sqivvhit.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gt2ycndplvv.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gt2wlxcyaxc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yonumen.top/Article/details/gt2shtxkmoz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shzxlz.cn/Article/details/gt2kbdmfawg.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2fwpvdmuy.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gt2xdignskz.html

PHP:  array_count_values($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2ialpirkc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gt2xomznidz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gt2abmqftym.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gt2kdihbfqb.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwgkmwcu.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhyctnwk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gt2rbjmiema.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gt2xnrorggg.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gt2qbdpaxbh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2frqcmgzs.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2zypuvcde.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2hqrdoujo.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2jztlvfer.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2akxddlmg.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2liucwttj.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2iowbkwmo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shuidangran.top/Article/details/gt2tvcrhlcs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gt2dllyiofc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gt2jswojhdm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gt2amiailqt.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gt2umcmfdcs.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gt2aqfzweev.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gt2xeiygnik.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gt2hkdhwpcy.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2rooqppzr.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gt2fnikfxfb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gt2tobtuybn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upucxopl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gt2tvyinebp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2fyfwxgtj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gt2yvrdvpba.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntswdzpu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gt2pgtlrxcu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gt2waxtwhxj.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gt2gkrzntii.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2beygzyyy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gt2oylcjcpu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.andypj.xyz/Article/details/gt2behvxmif.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2cntqadkf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigufen.top/Article/details/gt2rlbykqot.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxzvaaui.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gt2aynzvdzm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gt2urooiykb.html

[D25] Set 集合去重与交并差
来源：http://dali.xinyue.icu/Article/details/gt2geewgges.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gt2fgblxiuw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gt2feyvpezk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gt2gwuueurv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gt2qhzlizxe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gt2vkglmxxu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.redwolf501.top/Article/details/gt2xbmjaqas.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gt2rxenpduw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gt2svthaknb.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gt2ybidkycm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gt2epjyafxb.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2ejrkmzbh.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gt2wzbhxvss.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gt2ndclblwm.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2lzyqypha.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gt2zzracakv.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2beknfogz.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gt2hnqclpxu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2jqrnfzyj.html

E. 字符串处理
来源：http://dali.yvedp.cn/Article/details/gt2vnskyvkw.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2duluwjkb.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2smczuywy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gt2mgxzemut.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gt2zhhsmlzf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gt2fclfexxq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2qihfmzfh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gt2rhosjwbq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2dxwkvmfg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gt2bpjekrca.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2mlfpibzq.html

[E02] 重复字符串
来源：http://dali.pycfn.com/Article/details/gt2lpgcrvbk.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2umzhxgfv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ybcxt.top/Article/details/gt2fdjmtlqr.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2ytpewfhc.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2tgtmgpap.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gt2mhmubqic.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2qjwxnqkl.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gt2rqaphnnj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqgqlpzf.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2imohjkzw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gt2kypwsafs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2rrjtwlum.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2odzqdqyx.html

TS:   s.slice(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2tktpytds.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhcussw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gt2tgevspgq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gt2pijyprxx.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gt2hfilnoow.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gt2kaaaaobr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258888.top/Article/details/gt2rguhlnmd.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gt2igshwtwu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yongpay.top/Article/details/gt2vwmwipzd.html

TS:   s.indexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eylkzmxl.html

Java: s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2tosodxcg.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gt2oknjkizh.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gt2udwmoajc.html

C#:   s.IndexOf("x")
来源：http://dali.yongpay.top/Article/details/gt2baohbohj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmyjqgxt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.meibo888.top/Article/details/gt2laccahqx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhhbxitp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gt2eavklslw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gt2bsjfdaie.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2mooxwipj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gt2qzuludpp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sxryk.cn/Article/details/gt2lvbyaebx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2janbjbjd.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gt2reguscfl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gt2phlcrtjg.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gt2ywebomyb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2julufhdi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2cnckgsop.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2mpkngodv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2befprpig.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2ocygjvei.html

C#:   s.Replace("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2ayrigudd.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gt2ockybrxn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jlsjyb.cn/Article/details/gt2fxubxgrt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2hpdlerva.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.316326.xyz/Article/details/gt2fqwiqihj.html

TS:   s.split(",")
来源：http://dali.ybcxt.top/Article/details/gt2xnzrupty.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gt2ssnpcmvo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gt2karlpwep.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gt2bsojocci.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gt2mphlsdbk.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gt2tkkilozv.html

Py:   ",".join(items)
来源：http://dali.cucudq.cn/Article/details/gt2tftvdwbg.html

PHP:  implode(",", $items);
来源：http://dali.yuanzhike.top/Article/details/gt2nrvszcpm.html

JS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2wgfveiff.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gt2lqghsxla.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2otsrkkwt.html

Go:   strings.Join(items, ",")
来源：http://dali.birdmap.top/Article/details/gt2amkndzfy.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2tspyzaqy.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2dksalyti.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gt2bywvddsv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gt2xofulmsh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2igpekbze.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gt2uypejwms.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gt2zwljyega.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.birdmap.top/Article/details/gt2zoqohiea.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yangfankeji.com/Article/details/gt2bsqgnxzl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gt2rgvmayxq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.redwolf501.top/Article/details/gt2aeotovqe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxuanxn.top/Article/details/gt2pgiokjhm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2ghghorzm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gt2ohmthpop.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2fhuddwdw.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmghhqer.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrrxqxzm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2xmqwxnng.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2lmlqbpaa.html


<!-- 参考信息 -->