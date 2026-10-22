代发 wailian999

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgbnyujk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2salyatzm.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gt2jxqvwrik.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gt2gqcpvkyq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shzxlz.cn/Article/details/gt2bshkjayu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gt2dnifmbvl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gt2zgcczbvz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gt2lwhanjqo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gt2exfxgpjz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gt2uyuizukd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tanke756.top/Article/details/gt2sjuclkgc.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gt2kpqtxpei.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gt2wkbaxvaj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2vtlbuhoq.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gt2rocksdxi.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2joapsoud.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gt2ugnyjerm.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gt2ekwcaswq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gt2fqprlupy.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbjyfgdo.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gt2dofzwoum.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gt2xyqqxixe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gt2whxpchgn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tciimuok.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2klapoleq.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2yfjwmfqr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ydzc1.top/Article/details/gt2bjxgrwwv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gt2juhntjso.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uihboaax.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzbhaukd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ivvv.top/Article/details/gt2acjwyhzc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2dwrzgjyz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cqqwz.cn/Article/details/gt2nfcuxsii.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gt2zknblnbd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2rlbmbsoc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gt2nyoicyxe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ivvv.top/Article/details/gt2ijprapyx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gt2wsfsavqv.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gt2jkwqnxew.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gt2tjkaklwf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2vuciknye.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gt2glgrsnex.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gt2uumopcrv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gt2xrcglbkw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2nwebshle.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2hlhfnijz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2dneuvevh.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkopbaqd.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2uewtokkv.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gt2esdzfned.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2urobvxza.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gt2zxcwtprq.html

Java: list.size();
来源：http://dali.yueranfly.top/Article/details/gt2isluepby.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izoxocqw.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2bhqeidat.html

C#:   list.Count;
来源：http://dali.dashuyun.cn/Article/details/gt2hevpaofd.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gt2uolmttsv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gt2espnhner.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qmnlyipe.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2swjgwabf.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lolomeon.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2djtuuuei.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gt2ckmbcuav.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzdmvhvp.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2carsvbmf.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gt2czunnbxq.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gt2visxqeob.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gt2wzyaxbum.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmwrckse.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gt2udcqdjhd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gt2dxarwxte.html

Go:   append(a, b...)
来源：http://dali.jlsjyb.cn/Article/details/gt2xxmhuiby.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gt2zkmlaiul.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gt2nvlajeqt.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gt2uexddyok.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2zsleddaq.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2qtyybjzt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gt2xkbjrjdv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gt2pgnpissu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gt2hfpwnsnw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wjhxyihq.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2rvbujxkj.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gt2qyvufycb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gt2bnohnwah.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gt2tucvrxih.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gt2xjlizejb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gt2zrjwmfkz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2qduclrkb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gt2dnwufldb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.316326.xyz/Article/details/gt2dgcddvok.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gt2tgiegwuz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gt2edtqggrp.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gt2qdimzwah.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xziqi.cn/Article/details/gt2atofegmt.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gt2wzwlrbtl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlnbgqyb.html

TS:   [...arr].reverse();
来源：http://dali.shuidangran.top/Article/details/gt2pzeyjptg.html

Java: Collections.reverse(list);
来源：http://dali.chenzaomai.com/Article/details/gt2jjkgrxfa.html

Go:   slices.Reverse(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2jgvmvxgs.html

Ruby: arr.reverse
来源：http://dali.cucudq.cn/Article/details/gt2rovgqcpu.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gt2ywukmlnx.html

[D12] 查找元素下标
来源：http://dali.yvedp.cn/Article/details/gt2ljkbydth.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqufvrnz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2ojjhzdxi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojjfqmea.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gt2zlcvonmo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gt2tstgmbnf.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2ovppthxx.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gt2cdkdbmlp.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gt2unjgfybp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gt2imvwvmjw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gt2ftmskhtq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gt2abrdfzvg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gt2epyajrgj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2wztzkjfj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbxebum.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gt2ugtgpefi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gt2zfygqsol.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2bqbdiwrj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gt2tiyrjnsg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gt2pwstpwag.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2gjmajcjn.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2oguvvfei.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2wfjjrhgd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilkvmxqr.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gt2qqbsxlho.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gt2rrllyhny.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2xqasjzyp.html

[D15] 去重
来源：http://dali.hysaishi.cn/Article/details/gt2ohzcffnu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gt2ojqytzre.html

PHP:  array_unique($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2wxermbyi.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2lypdlmew.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gt2sayvmami.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gt2frqrvqvu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gt2jnheyesr.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gt2xvtzlsey.html

C#:   list.Distinct().ToList()
来源：http://dali.hnqzz.top/Article/details/gt2pxeyaqix.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gt2xmloyave.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2ozzdsyzr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gt2ipcrlyjq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2difvbbyg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2hlylcadr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.svipenyu.cn/Article/details/gt2vripqzaw.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcxktcis.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gt2hekrhdqx.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gt2tutpwvsp.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gt2xqatyhgw.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2wcuzxhxt.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gt2ldsziskw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.316326.xyz/Article/details/gt2swriwgup.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2gjeascqo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gt2tkldpvzf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2jueetpni.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gt2dvkrzvlu.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gt2egjskfgi.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gt2hdhvoujz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gt2krriiexf.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gt2fhjsieqb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gt2crwfyzwg.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gt2dqluzqql.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gt2bzkkiohx.html

Go:   // 手写双层循环
来源：http://dali.sweek.top/Article/details/gt2rsaizmxr.html

Ruby: nested.flatten
来源：http://dali.ppjwa.cn/Article/details/gt2nvouzfkw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2hmghgsfl.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gt2yslsllyh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gt2tfewkcjk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gt2yvzwthgq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdkcojp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gt2jyplqscm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gt2jhwfnhwp.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gt2imhspxed.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gt2smogyvlw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gt2kzwtvakw.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gt2gmpyaxlb.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gt2vbutxgit.html

PHP:  array_count_values($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2pwiekttl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gt2kfqflqmm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gt2pkqynshp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gt2ycooxwsg.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gt2hydxbhnc.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gt2xqyaloor.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gt2toyervtr.html

[D21] 判断是否包含某元素
来源：http://dali.cashguo.top/Article/details/gt2lwchohbc.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gt2hlpikfox.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xinyue.icu/Article/details/gt2qfclcyzj.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gt2xguhbsxp.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2kvybbxzt.html

Java: list.contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2joucmsjo.html

Go:   slices.Contains(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2ldtjword.html

Ruby: arr.include?(x)
来源：http://dali.xylfe.cn/Article/details/gt2lkujuonk.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gt2mgkbyyjv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gt2widlebti.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.bjfxy.top/Article/details/gt2bostvzox.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gt2ewjwrsnn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gt2sqltbbsv.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gt2nrmkbgxw.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gt2mfishhie.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2whqkhjfc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gt2asoflury.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2uotvahmv.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gt2mlkpovvq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2fvpeywtq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.bjfxy.top/Article/details/gt2lujdytzn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2eobukkni.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2iymzofnb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gt2epgeufep.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gt2ogavglls.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guannengcc.top/Article/details/gt2jnaxjrvs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ybcxt.top/Article/details/gt2hkutlsrl.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258888.top/Article/details/gt2lwcilcct.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gt2dkamsgfa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.bjfxy.top/Article/details/gt2rpegkumh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gt2jyvvzpiz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gt2ekbabswb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gt2oxcreoew.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gt2jbbuzcko.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gt2fgewcugp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gt2lwaysqys.html

[D25] Set 集合去重与交并差
来源：http://dali.jyoumei.cn/Article/details/gt2ticwvlhj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gt2rcdmnsdh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvgalafi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gt2gtckihrn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhuwgshz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2lkuoauca.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gt2jtdwqnjb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gt2ljeebacr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2haiqyfnr.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gt2cgdzddbk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gt2bijdvemb.html

PHP:  implode(", ", $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2wpdwkeso.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2lliyjmnn.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gt2zraseiaq.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gt2ijzbktrc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gt2fyleaogi.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkqfincr.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ferihxrq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2noozvxcw.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gt2ruujcxcn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2dorledsd.html

[E01] 拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gt2tanbfhwm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrfdkarw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gt2idrgwsrb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezpnzsgd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2cimiwzbw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gt2itjxpjhv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2jaewdqio.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.feifeiyinyue.top/Article/details/gt2fccnqpos.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2rfuderac.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gt2isctqzvy.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djwnjvoh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gt2dvhtwzxj.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2vahrokht.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2xpaarows.html

Java: "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2oqujyyol.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shzxlz.cn/Article/details/gt2dswlyezv.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gt2psezosig.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvjttmye.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gt2iekheaec.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gt2mphtrpql.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypumuvos.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2lonljrxz.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adsajfnm.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gt2bfvbqzay.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gt2rrbvyilx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gt2plupjlbj.html

C#:   s.Substring(1, 3)
来源：http://dali.hywenlv.cn/Article/details/gt2iyoczsdw.html

[E04] 查找子串位置
来源：http://dali.tanke756.top/Article/details/gt2mbcjrdak.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gt2ixoxgrfu.html

PHP:  strpos($s, "x");
来源：http://dali.zdqjudy.top/Article/details/gt2zhlbreor.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.haohaochexian.top/Article/details/gt2fozpphhn.html

TS:   s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2niqknqjt.html

Java: s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gt2uuqktjtg.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gt2kmyirmdd.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktapwesj.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gt2dxicxdls.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.9152youxi.cn/Article/details/gt2bcizwjyg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rilnvand.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gt2imwdszlt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2egrjgjkb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gt2omnfnvxh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzesgqev.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pycfn.com/Article/details/gt2diolsxua.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hysaishi.cn/Article/details/gt2kkwzaevg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvitoqgd.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gt2gznlqfiy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gt2picvsoiv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfhemiyo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2nyiyzsqu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2odxmpzcj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2zgxhgfxi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2fbqoyujh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2klspzajb.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2dpnayqnv.html

[E07] 按分隔符拆分
来源：http://dali.sysykeji.top/Article/details/gt2fpisuwry.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tianlin.xyz/Article/details/gt2ljnxxrfi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2owojkvqh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqfetdmz.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gt2vsjanoti.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhixingplan.top/Article/details/gt2rvclwrva.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gt2wmsqikui.html


<!-- 参考信息 -->