代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hysaishi.cn/Article/details/gt2ppuhpujo.html

TS:   arr.splice(0, 1);
来源：http://dali.cqqwz.cn/Article/details/gt2ejlqojdk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gt2xfwnzcol.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxspkpps.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yuebtjaw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daxiang520.top/Article/details/gt2gbhvbztl.html

[D05] 访问与修改元素
来源：http://dali.cdnleiting.top/Article/details/gt2jbcdcmrv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2bndevpan.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2dfbwbxwj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2rvuhcjyv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gt2zxlrfhem.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gt2moepvtdc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2jzndhcko.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2njsuflcz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2rqndeyyf.html

[D06] 数组长度
来源：http://dali.c1oappe.top/Article/details/gt2kbinmguh.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2pymwihmr.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gt2rozzgobd.html

JS:   arr.length
来源：http://dali.tanke756.top/Article/details/gt2tdsunwtt.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2nwhbjxtw.html

Java: list.size();
来源：http://dali.andypj.xyz/Article/details/gt2ajtlycrx.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gt2spglseri.html

Ruby: arr.length; arr.size
来源：http://dali.xziqi.cn/Article/details/gt2uvrjhqrq.html

C#:   list.Count;
来源：http://dali.haohaochexian.top/Article/details/gt2lwnilhyl.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gt2qvqdyfkm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gt2wtgsopja.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2keguhdct.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2jlzaiewx.html

TS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2opsfetru.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2iaxkgyjj.html

Go:   arr[1:4]
来源：http://dali.shuidangran.top/Article/details/gt2xfxpzpgg.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2ftksdfei.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gt2uqwplpge.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gt2nqavdamk.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gt2waowmwsw.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmssbkeg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gt2dclvdrdf.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gt2estlypqb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2yrvejvjz.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgigpfgz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gogol.net.cn/Article/details/gt2otfsuhrh.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2mxpbouyh.html

[D09] 排序（升序）
来源：http://dali.hnqzz.top/Article/details/gt2dpggkcac.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gt2jsfcvkzk.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2rmycwfow.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2adcannzq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gt2rdfmffec.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gt2atfhkfgm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gt2wsixftvw.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gt2pidtcijm.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gt2mgosawxj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gt2kzwrlbnk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gt2ewpnxzmy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gt2niwlbbag.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gt2dlguobek.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gt2czzsobyz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gt2ytkqmfwy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yangfankeji.com/Article/details/gt2ozlkdess.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gt2ufxkesag.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gt2xjaayuas.html

[D11] 反转数组
来源：http://dali.cdnleiting.top/Article/details/gt2iylsyxkc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gt2pyjpsjgd.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxnlcogu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gt2bjxnlgha.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gt2ingswxjr.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gt2qmuumkfm.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gt2byzvsyec.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2yriupvbo.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2knaridns.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gt2hwiwdnyp.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2oivuggex.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrsuhhjo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2akdhrfka.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2fxohpeyj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gt2gkryhhub.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2cuakgcxe.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2ovneccwu.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gt2udkaaeko.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbtalvf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sysykeji.top/Article/details/gt2jhidjkzt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gt2bsabmknz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gt2yqjhwqmd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gt2owiltran.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2hovemgab.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gt2vdypbcrd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gt2hhuzqcbv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2bysxkxnm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.quarkkingdee.top/Article/details/gt2mlavkiif.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2blrzvzqh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2njdfesxo.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gt2vcyenxoi.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2irminofh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gt2tgeeeroq.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gt2lkltrhoi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2ijyeqosc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2cltlzxqu.html

[D15] 去重
来源：http://dali.fengsongda.top/Article/details/gt2ktbvokil.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2ozkrlvym.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuhnkigz.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2yakvmezv.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gt2mfgoexlo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.vqdsnc.cn/Article/details/gt2qgxuggzc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmbnkgid.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gt2xzusokdo.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gt2gqqqailt.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gt2vncydjva.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2jtvcxhxi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zycfv.cn/Article/details/gt2takfhkls.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2vkuhexkr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2ugzmknjw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hywenlv.cn/Article/details/gt2eowhrbkp.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yobgkfjx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2fidujwoc.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gt2azxrtcud.html

[D17] 最大值与最小值
来源：http://dali.quarkkingdee.top/Article/details/gt2whethkip.html

Py:   max(arr);  min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2umwewgtx.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2wbxituhy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gt2hpxmfgza.html

TS:   Math.max(...arr);
来源：http://dali.bjfxy.top/Article/details/gt2yveymwrs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gt2yykhpyie.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2ovmlfyso.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gt2rnjlozzz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gt2ngtnxtye.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gt2yigiuwma.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gt2bmwhxqdq.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2kauemhgc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jatttdfe.html

TS:   nested.flat();
来源：http://dali.hfpthk.cn/Article/details/gt2ualrbeaz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gt2utrritsr.html

Go:   // 手写双层循环
来源：http://dali.yvedp.cn/Article/details/gt2qakmbcza.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jchjrola.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2mlzhperf.html

[D19] 按字段分组
来源：http://dali.shuidangran.top/Article/details/gt2hlqwtrqp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gt2kvqnoulb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gt2ccjyffcd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmzctvku.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gt2ezqmgjmw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gt2rmohyagw.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gt2wijirffm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gt2eeclivec.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gt2dgokklvl.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gt2rgynuckh.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyoirzzn.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjdnicpz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gt2bfvpuryq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gt2oslalmri.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gt2jgkpgmok.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gt2ofmsxsfi.html

Ruby: arr.tally
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2voauvewl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gt2ypxbaihc.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gt2eikjkwoy.html

Py:   x in arr
来源：http://dali.guowangkeji.top/Article/details/gt2zplcckdq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.0kj1m.cn/Article/details/gt2ifzkquzt.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gt2qlbkrkeb.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmjmpfme.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ewgkruhk.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2bqqsryux.html

Ruby: arr.include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ujlyknsi.html

C#:   list.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2tesvcvnb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gt2whrmqkvk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2tlmpurjd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gt2tywrzand.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2egkphrun.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gt2uhloszjd.html

Java: new ArrayList<>(list);
来源：http://dali.birdmap.top/Article/details/gt2quumodrd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigufen.top/Article/details/gt2nuyogosc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gt2fznddonu.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gt2rerniucu.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gt2ejxaomxz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2jzcwgxeb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2efuhgfhk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2snazowjk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2sdvcisao.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gt2jiwyfxhu.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gt2alekbktv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nwbrower.top/Article/details/gt2pwfwtejl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sxryk.cn/Article/details/gt2epywkdep.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gt2mqrbgggx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shuidangran.top/Article/details/gt2yjnyxsae.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tuwvzilk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gt2sliageqs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2jpdydpwd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gt2aetmzvsf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gt2toapyldh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gt2atcugyyf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gt2jigenzyr.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gt2mihnahej.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gt2ffaeehwu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daria6918.cn/Article/details/gt2jaehykqm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.birdmap.top/Article/details/gt2nrdkohtb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj202588.top/Article/details/gt2zyhhrurd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gt2wjnfgvey.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gt2ysscbzyd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gt2ehhmjczm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnqzz.top/Article/details/gt2xbmbbwmq.html

[D26] 数组转字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2gowgeepx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gt2lvhuvtth.html

PHP:  implode(", ", $arr);
来源：http://dali.yongpay.top/Article/details/gt2fuzopmhe.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2stwvibde.html

TS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gt2lzcsibqo.html

Java: String.join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gt2rvygrbio.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2lytcatzq.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dehrbapf.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxilhevr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2wyxpfmyp.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gt2avhwjjkg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2etsdxlzh.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2ygnkdodf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gt2aadvpskr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gt2iggjajzh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2xhifxhtb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gt2bucioxjx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.guannengcc.top/Article/details/gt2ehbmrjsk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gt2jdlzmjuo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gt2arfvffzc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2gymcgivs.html

[E02] 重复字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2rqgqvrlj.html

Py:   "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gt2cxixdyjz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aizwys.cn/Article/details/gt2pbuckxws.html

JS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gt2qupvablf.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2guzsyqiu.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2baxbuuwb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yueranfly.top/Article/details/gt2agjsxstr.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2nwezuojz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gt2srelejss.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2csfuhoql.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sxryk.cn/Article/details/gt2qsaumnru.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2pnjuwaxb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2tvlldgkf.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2cjavuwzv.html

Java: s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2jljfcryl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dianchejie.cn/Article/details/gt2kdsobqks.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gt2mjdnjcgz.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gt2egzuqilw.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gt2ediiobup.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenzaomai.com/Article/details/gt2stfoutdb.html

PHP:  strpos($s, "x");
来源：http://dali.shzxlz.cn/Article/details/gt2bknwgwfh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxuizcid.html

TS:   s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2daguymwd.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gt2dlirochu.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gt2bqsattem.html

Ruby: s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2wrcbrojp.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2mtvjeziu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258888.top/Article/details/gt2phlqulyx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenlongwang.top/Article/details/gt2pdukvgil.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gt2nigycwqi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2mmyniaaf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2picbovxi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2nrtzikqq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gt2efhsiygu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gt2owhejcqx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2uzrgvzmk.html

[E06] 替换子串
来源：http://dali.dashuyun.cn/Article/details/gt2pkhvenvb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gt2bpwbjajs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gt2yndznnen.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2dtgngxnb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2kxcyprzl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2gworfrgn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2bdwsctee.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2vtlykkqu.html

C#:   s.Replace("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2rrzmojfe.html

[E07] 按分隔符拆分
来源：http://dali.0kj1m.cn/Article/details/gt2eazkgxtw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yj20258.top/Article/details/gt2xupuhorz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sweek.top/Article/details/gt2kcleqyxu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tanke756.top/Article/details/gt2kvhnrlui.html

TS:   s.split(",")
来源：http://dali.guowangkeji.top/Article/details/gt2xbvoxojw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sweek.top/Article/details/gt2jgheqadl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcxwynmh.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gt2wacopbie.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.bjfxy.top/Article/details/gt2gwprgori.html

[E08] 数组按分隔符合并
来源：http://dali.pycfn.com/Article/details/gt2gvvlmlky.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gt2qanyrymu.html

PHP:  implode(",", $items);
来源：http://dali.mhx1999.top/Article/details/gt2lphqmwov.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gt2quplgzkj.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mycuoeaw.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gt2btbxllnz.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdnvfbig.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2xsakxixf.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gt2zjpwtzjf.html

[E09] 去除所有空白字符
来源：http://dali.haohaochexian.top/Article/details/gt2heyzbwkx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2gchjlmke.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gt2gnewjjul.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gt2ftoxowyz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgstjbef.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gt2kphgahdq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2oyewysrh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.andypj.xyz/Article/details/gt2omzhdjla.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gt2vuamxcnv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gt2tctwolpj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gt2dnodlncc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gt2hqesfcgk.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2khurvmsw.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2hgsdlskm.html

Java: String.format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2ldvenano.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2qbhgzrkm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2dfquinva.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gt2gunocuhc.html

[E11] 反转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2mpycnrzm.html

Py:   s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gt2dduhzfqf.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gt2vnrabrgm.html


<!-- 参考信息 -->