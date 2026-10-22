代发 wailian999

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gt2lprdzoec.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gt2udujynfw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gt2tptxncqs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gt2fxdarswm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gt2pygtrrre.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gt2ubcxqkks.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfehulsn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2sjnklhpv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gt2sgntbznh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2aqpdjzhw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gt2dyjynpui.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gt2tfbovpdv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2vgvxckrm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2cdpedhes.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2mgbhhwuq.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2twjrtuvz.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnctdett.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2simpsoje.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2akdilkcw.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2duuzqjkk.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gt2ehgubxpi.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbvaxino.html

Ruby: arr.length; arr.size
来源：http://dali.gogol.net.cn/Article/details/gt2gercrslo.html

C#:   list.Count;
来源：http://dali.xylfe.cn/Article/details/gt2mjtoqdll.html

[D07] 切片 / 取子数组
来源：http://dali.cashguo.top/Article/details/gt2jrjutrwx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gt2aacatraf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gt2jykfqlbe.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2xuhdjtoj.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjcnysfn.html

Java: list.subList(1, 4);
来源：http://dali.havefunace.top/Article/details/gt2btlmvddr.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gt2fmlpcace.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gt2yecmvvkc.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2lunigjyk.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gt2ywwrftfu.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gt2wnmbzbif.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigfzy.top/Article/details/gt2ndlvcxiz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hywenlv.cn/Article/details/gt2rkukonps.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gt2bswxsqjs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2spoyzbel.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwjsyvuc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gt2xnsltafw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2mxjktdgu.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gt2vtxzwycv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2obffltxc.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdvtnfjv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ppjwa.cn/Article/details/gt2rkeqxszv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gt2qgkgbhjb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gt2rsskskaf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmtbxjel.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gt2qwbdclgm.html

C#:   list.Sort();
来源：http://dali.jqgufenzy.top/Article/details/gt2exvvvyqz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gt2ynrcagho.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gt2ammlilto.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gt2akstuacy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2lwrfprhi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gt2ngvkvrsn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gt2wwgfotyn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gt2hltdcjhp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gt2fskyojyf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gt2kqlwbdjm.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gt2jqeyjpej.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gt2tswzdsda.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2qpollksl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gt2gpcxuzzg.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gt2asvfquph.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gt2jbytbico.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2sqmlyfcf.html

Ruby: arr.reverse
来源：http://dali.yonumen.top/Article/details/gt2yyvexyol.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gt2mqdwboqu.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gt2xcetafdf.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj202588.top/Article/details/gt2yiamzihv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2yoldjdnf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gt2btvnzvex.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gt2xzswlcbc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nwbrower.top/Article/details/gt2jmtsbgkt.html

Go:   slices.Index(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2oiryciqs.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ampatnxo.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gt2spjnpvmn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gt2lxqwmuow.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2esyepoby.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2bjbqmnqs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gt2afiqmtoz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gt2jyzozdud.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gt2hlnevsiw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enwwqatj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gt2uywuazqh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wgwyhulz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fzhhl.top/Article/details/gt2keltcozn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2smqnalkk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdfufiav.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gt2xrjvrhyn.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gt2udlucoyq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2rrewcwpz.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohztyxbf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2gqblpszl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2oyfbwfuv.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gt2frjubhyq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gt2vcrrvxeg.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2vapolpit.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsdpuitb.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjkyteik.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gt2mjvbbxvz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gt2prejbyyz.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gt2xkrbnnyt.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2uytvryil.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gt2hcbbuprf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2dkxfypsx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2iogopzfh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2vaqsipvp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2ulwfikcq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gt2jhtruwrn.html

Go:   // 手写循环累加
来源：http://dali.cucudq.cn/Article/details/gt2muhgqfez.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwxdzqfc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gt2hresrupk.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gt2uozjxakz.html

Py:   max(arr);  min(arr)
来源：http://dali.jianghu66.top/Article/details/gt2sdakjxtc.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2ysivibyr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gt2zulhuznt.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gt2dscwubfu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gt2pittszvw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovoxmmab.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gt2wfqvfdea.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gt2khbpikrl.html

[D18] 扁平化嵌套数组
来源：http://dali.quarkkingdee.top/Article/details/gt2wnfzmsdu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gt2sfxpjtyf.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gt2xrrpdmvk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gt2fstbltir.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gt2exwsdzbj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hammf.cn/Article/details/gt2znderrje.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gt2mhetujsr.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhppgmtp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2qdxlzcbt.html

[D19] 按字段分组
来源：http://dali.wangdashe.top/Article/details/gt2suaewwdq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gt2ewnpiosy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gt2folepold.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuanzx.com/Article/details/gt2vecimxbm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gt2kyljcqrg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gt2bcdsrszl.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gt2niragpvk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gt2xwwzbalg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gt2esrdvxid.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gt2gsxhayjb.html

Py:   Counter(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2gsrtqzxw.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2bqruxwax.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opwfmdmg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2btfifpgr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gt2hdazbgqi.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkdrplsd.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gt2dygslzmd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gt2mhdfrxuy.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gt2baazqiai.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gt2bjttgssz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sgevfwkd.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gt2vseqikhd.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2mtyqadxx.html

Java: list.contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2ogmfdzjl.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2lvwsmmkb.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gt2dxsjvbbm.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2iveppjxd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangshuangyany.cn/Article/details/gt2flmshoon.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gt2hkwkbnul.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gt2jouwxgyc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gt2pllihbnn.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzgkllol.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gt2kapcvefi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2ulydbgno.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gt2qvfgvklx.html

C#:   new List<int>(list);
来源：http://dali.ybcxt.top/Article/details/gt2njigzaxh.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gt2gjhvayyr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gt2tloebvgw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfyglbxq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvjvaiok.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gt2upfdwgbm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gt2tidvxmzg.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gt2tfzguekp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gt2fzqztkgg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gt2brvdtjnv.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gt2tmtvilxx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gt2smxximjr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2rimjkuja.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hywenlv.cn/Article/details/gt2wegullvt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2yawwkzpe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gt2brwewdod.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gt2zubesyyk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xylfe.cn/Article/details/gt2riqkkyzg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gt2wltyskyb.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gt2tixztfvy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gt2lsstwfge.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gt2obzchbwz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gt2sjeelfzu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gt2vozwsqxt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2ucjexmap.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yonumen.top/Article/details/gt2ojtavgie.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gt2ycqpegyr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cioqosqr.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gt2owkqqahz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2cyhcxyzy.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqbaijvl.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2qzpzcptw.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sgrpeiuu.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gt2lxqnostz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gt2gawlbopv.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlzyojeb.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2zmwjcxwe.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jtvpjhuc.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gt2fvwfbezd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2wtlkdypd.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozvohqgg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gt2xokfdtfk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2imcjylvg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gt2foidluct.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gt2aanjvmae.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gt2swpraici.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gt2edrstrfl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gt2ncnlcjzc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2ovjnkleo.html

[E02] 重复字符串
来源：http://dali.meibo888.top/Article/details/gt2tvfhfirq.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gt2kbuinjuf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gt2rimtwbvt.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2ivbfcjtl.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fsjnecrc.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2ompjthiq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daxiang520.top/Article/details/gt2hmxwrcxc.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2whechyrw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.redwolf501.top/Article/details/gt2ywnfwwjq.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2wvhcctzy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gt2cmdratrc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2pzbroncb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wyujpcsn.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gt2akirzuws.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2cabpiphs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2tbyndacs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gt2tqhstwtx.html

C#:   s.Substring(1, 3)
来源：http://dali.havefunace.top/Article/details/gt2bateyrek.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gt2ggqlymeb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gt2axkzlwrd.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gt2wvbdzfjd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gt2ircwyfrr.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2xkgzcibd.html

Java: s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2djkhukzh.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gt2lywposyq.html

Ruby: s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2aznpdsks.html

C#:   s.IndexOf("x")
来源：http://dali.zycfv.cn/Article/details/gt2zwjaqsof.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sufxvd.cn/Article/details/gt2fyfywwgg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gt2xeajzuuu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gt2mxilmbln.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2imbjwgqv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.iojbl.cn/Article/details/gt2ikwmghbl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.bjfxy.top/Article/details/gt2xmdxjmnk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gzhubu.top/Article/details/gt2biimqajs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jiagoushi.top/Article/details/gt2hjfystub.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2fmkylqev.html

[E06] 替换子串
来源：http://dali.cdnleiting.top/Article/details/gt2dvwkobcf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gt2qzsaervf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gt2hpqlohsw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2hbtmidie.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2bnufqdgl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2vgenvviz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.daxiang520.top/Article/details/gt2yoatjbqt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gt2poeumlwt.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2shxkngpt.html

[E07] 按分隔符拆分
来源：http://dali.mhx1999.top/Article/details/gt2iooxlyfd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvdezfyi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2bncosdqx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xuanzx.com/Article/details/gt2quafndgs.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gt2aikjsbzx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gt2pszqfltu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmydgjel.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gt2zicryihy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenzaomai.com/Article/details/gt2tzqlbkfl.html

[E08] 数组按分隔符合并
来源：http://dali.hnqzz.top/Article/details/gt2gurbngtf.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gt2ytelbzgr.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gt2iufqmoqe.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gt2bbbcftwe.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2ibcgzbrj.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ifvfxhwh.html

Go:   strings.Join(items, ",")
来源：http://dali.iojbl.cn/Article/details/gt2vqmczsyc.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2zdpkqezw.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2socoyljw.html

[E09] 去除所有空白字符
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgeqnvao.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2fvzopccj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdolxzsn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2mmrkeeut.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gt2gkfoveos.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gt2qmwoxauk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdrfqxlr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gzhubu.top/Article/details/gt2efgcicaw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gt2iwwexggl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gt2eyqwdotu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2jnmimpja.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gt2wfwmerte.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2bljlqbgm.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ardvrdex.html

Java: String.format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2biegaesr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2zkvazhgp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmgkvbct.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gt2ekpgsaco.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gt2ejsfhvpq.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2eqrktjsi.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2qxobctvf.html


<!-- 参考信息 -->