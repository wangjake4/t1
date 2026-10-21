代发 wailian999

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtmtgvbfvo.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gtlueyzzpa.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gtnprhwfbq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gtawmfpydc.html

PHP:  // 无重载
来源：http://dali.hysaishi.cn/Article/details/gtkjzkgofl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gtgjjzhayf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gtulfnlprm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gtotqihibw.html

Go:   // 无重载：用不同函数名
来源：http://dali.hysaishi.cn/Article/details/gthfdvgbye.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gteavarsso.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gtfyeupaaw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtoqkadgom.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gttqhchoth.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcknnqszc.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtxtrlykan.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtebazoren.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtcsnnilvn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtdfmxjvei.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtujvmljoj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gtnbehvrvr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcrpbnjz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gtkjznmnzf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gtwgquipxt.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gtgowklrpw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gtbmrrpkse.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtjrjkbwzj.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtwvvnxqdc.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbfqmoeo.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gtspqizqdg.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxogtdlv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gtfznjptix.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gtdmudnidm.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gtkrvgnztb.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gtnpfjktwg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigfzy.top/Article/details/gtjoximiqj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gtxgzdhtcf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daxiang520.top/Article/details/gtjfqzbrob.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtpraqrwvz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtrqjkqukb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqfgwdbs.html

C#:   list.Insert(0, 0);
来源：http://dali.sxryk.cn/Article/details/gtclgbftkj.html

[D04] 删除元素
来源：http://dali.nanxuanxn.top/Article/details/gtpacxmzev.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenlongwang.top/Article/details/gtzmktqdaz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gtjiljgnie.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.daxiang520.top/Article/details/gtvlverzke.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtlmxuppnt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guowangkeji.top/Article/details/gtblgxrqub.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.birdmap.top/Article/details/gtfjrbcbts.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gtpxouybqt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzqgfyfu.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gtvdkrmrdf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtuorifecm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtubzqbzph.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtfuaobjys.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shzxlz.cn/Article/details/gtoecexzuv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtftokicke.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtpxacfrjc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtzbpdjohn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtkijpsuip.html

[D06] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtbevoeelj.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtscpthzql.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtfcegzuzm.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtdsmaowcv.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtnfvsnzpk.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gtiaqemyyk.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gticrdvyha.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gtlmrbbhnp.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gtlfgaxxaa.html

[D07] 切片 / 取子数组
来源：http://dali.shuidangran.top/Article/details/gtuhrjiguu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gttkcjjawu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtsiqjvxmp.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtgoyuhcgl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gttymgvgqr.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtgbvutule.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gttpkcybmi.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gttbjifstg.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258.top/Article/details/gthmfvwxhc.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtzqsebgvp.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gtfkakcnzj.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtkqkdhfmh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.redwolf501.top/Article/details/gtgcfxnibt.html

TS:   [...a, ...b];
来源：http://dali.hammf.cn/Article/details/gtcunqznlj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gthpohwguv.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtivjsyzuv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.mhx1999.top/Article/details/gtgurtsqka.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtrwisjyxl.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gtlcqcyudz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtnmijlhio.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gtamavkyuj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhongyouzk.top/Article/details/gtezdqztqr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gtyrfobzbm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gteqbnvkvg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtljgrjdeq.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtqskhwzkg.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gtbcxvmnam.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gtxjfswrna.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenlongwang.top/Article/details/gtwvalnxiq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtlnmpzbnh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtjfbxjcjb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhhjesdz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gtatzfidtz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yonumen.top/Article/details/gtwqagxpzy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtmffzjlih.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gthwrdjtyp.html

[D11] 反转数组
来源：http://dali.birdmap.top/Article/details/gtmcinxqkw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gttqmzjcem.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gtkdvnwqwf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.redwolf501.top/Article/details/gtcerzzjuu.html

TS:   [...arr].reverse();
来源：http://dali.aizwys.cn/Article/details/gtqgvcrxzm.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtbyeoqehx.html

Go:   slices.Reverse(arr)
来源：http://dali.guowangkeji.top/Article/details/gtdnucolbt.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtqljxsqyi.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjijsbmr.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gtvkahvxyz.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtcdqhxrpv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaipyaivy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtsefomiqm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gtnmzdrutb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtipixoktj.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtlxaogzbb.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gtmmhzcyqy.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gtedgbhntw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.meibo888.top/Article/details/gthiwgrigu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gtykwhaoxo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gttkrsigbh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthryzwrgf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtkwmgdnkt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gttdiynjth.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gtmhxmjbee.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gteghzddgg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gtvvknfwdx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gtnydpxkac.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtisxvnwlc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gttwlkgmza.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtuhrfyipx.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtnwxdhqwb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gtmvkxcckw.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtlhxzmnel.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gtjyboojft.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gtfehodenk.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gtwdnjymvr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtnvebdxbu.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtcihhbgvo.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtozbqdmjw.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtaacqatlh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gtokffmetm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gtivuyzkgx.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtttkhefup.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gthfdaporj.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gtlhukyehu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtehjdukdd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gtjcpgqjxg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtozniuoym.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtjokafgut.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gtsruvpgqt.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejoyqiom.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtnndybkkn.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gtsmgogatk.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gtjvdbfwue.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtzbvtkmzj.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gtzcmcqsdq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtrocgfuyq.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gtdtxjjmya.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gtqmvvmbnv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwewpczub.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gtbhomppqw.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxuanxn.top/Article/details/gtiudmhubl.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtiglpygxm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gtnlgnxlgu.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gtdvxferpd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gtigtosmoz.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gtblztovpz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtjfrwoggw.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gtdrxebzeh.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gtnrulhmlf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gtykpaenem.html

[D19] 按字段分组
来源：http://dali.shzxlz.cn/Article/details/gtctrccyrt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhongyouzk.top/Article/details/gtcnavxtlt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtzkyxpctj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gthxqrvoqb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtibawbbdf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gtweqqypny.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gttwibemcn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtknbwhpxt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gtqxnprapi.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtuazimvfo.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gtrvdkvmdi.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gtyinvtchi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutbrkdzb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gtzgtdzhag.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gtvcfbmvam.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gtghqhqbaz.html

Ruby: arr.tally
来源：http://dali.tanke756.top/Article/details/gtkvsrudgq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gtuojeckci.html

[D21] 判断是否包含某元素
来源：http://dali.svipenyu.cn/Article/details/gtjdlflzba.html

Py:   x in arr
来源：http://dali.pycfn.com/Article/details/gtfaxpetrc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258.top/Article/details/gtlkyrzodt.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtjbsfboax.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gthbfkcwxf.html

Java: list.contains(x)
来源：http://dali.yongpay.top/Article/details/gtetlyltbx.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtymqaeajr.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gtloqcwwlk.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtulbbghhx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtikobgvyu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gtozzetavb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gtccrlpxos.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtlwwrshcl.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gtdrjpykls.html

Java: new ArrayList<>(list);
来源：http://dali.dashuyun.cn/Article/details/gtecuouhlj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtunxfhdxj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuanzhike.top/Article/details/gtlphrzyrm.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gtkseffqtm.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gtgdxfkwci.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sweek.top/Article/details/gtzvdidugx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gtxhpujswv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gtnnxarfow.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfeusvob.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtdttkauzd.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtjfyagaao.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gtqvuozudi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghkpuxao.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gtstaksjux.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guowangkeji.top/Article/details/gtqxnrffpp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guannengcc.top/Article/details/gtfhauxeeb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangdashe.top/Article/details/gtxrouooqn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtglmfltgn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gtogbhoylp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gtirqwgxel.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gtbmlfwblq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gteivndoez.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gtrscyeflj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gtqatsrswx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtnshfiiyj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gtvpbqwwsf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gtktzbpelu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtaosalxux.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ybcxt.top/Article/details/gtkyzxcvpj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zdqjudy.top/Article/details/gtlndhzdvw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtuctfzqcx.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gthxersvrz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtmutyidfq.html

PHP:  implode(", ", $arr);
来源：http://dali.ivvv.top/Article/details/gtxktkyrnk.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtpvdxbzrq.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtvauydrtv.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtraapszmx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gthqfueewn.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjxbnzbh.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtstkpflks.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtaukoisjq.html

E. 字符串处理
来源：http://dali.xuetiantiany.cn/Article/details/gtmkijdfpg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttrapghih.html

[E01] 拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtdkczeghg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gtnhrdygut.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gtgsuimgex.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtryhgvhvj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtkcqtfhfk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yonumen.top/Article/details/gtkhkudycd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gtogbubhow.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gttlkxveif.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtfxvvvsqt.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gtoxovevpc.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtfbqkxhjo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtbwfjvwhy.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtkhxvfmkp.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gttxugchad.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtqyktclal.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yueranfly.top/Article/details/gtmesbothf.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtqmecloek.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yanxiufei.cn/Article/details/gtztssczzm.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtvkqxsblh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nwbrower.top/Article/details/gtljxhihpt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtqjxrfamd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtikfdmqzw.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gthjpidiyk.html

Java: s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtylllzpbn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtamdlmopb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnqzz.top/Article/details/gtgtnvahvy.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gtauooszhm.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gtstyhtdjj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtzoybdorc.html

PHP:  strpos($s, "x");
来源：http://dali.xuanzx.com/Article/details/gtjgianbfs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenzaomai.com/Article/details/gtpemfciud.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtujtxjufy.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtbynqbtls.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gtdljmcvvk.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gtncwiuiwg.html

C#:   s.IndexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtacjhjwga.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gteymylxer.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gtpleherpt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtoeenolhc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtkshnmxdw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zdqjudy.top/Article/details/gtqqbjrspd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtvnlirqvb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hfpthk.cn/Article/details/gtfcnrwhfu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gtvyahulkf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cashguo.top/Article/details/gtyrfybocs.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gtugfvbgig.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtggklairq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gtzclmxklc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtudlujozh.html


<!-- 参考信息 -->