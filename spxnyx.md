代发 wailian999

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtjwjlpblf.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gtddjpppef.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gtwkinavpx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gtavyikhgj.html

PHP:  // 无重载
来源：http://dali.hysaishi.cn/Article/details/gtvknlgbmw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gtydmyoyhn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gtbsqjiwyf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tanke756.top/Article/details/gtgpjangdl.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gtbnpzcqkc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sxryk.cn/Article/details/gtopulpsdn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gtzhvwzogz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgxiaykmk.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtigpszbco.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtticckjpe.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gtugegfwpr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gtzfujajmt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gtxwvekiqz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gttunarccm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gtowfqlbyu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gtniurjuqp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gtqkrcsvuy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtjqkawhtc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guowangkeji.top/Article/details/gtmdssndag.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gtywvkcjfy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gtvvohngel.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtlnkhepgt.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtxdiihfct.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtonhmvgjs.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gttpckicmj.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gtfgmdnhtu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gtjogcygvw.html

C#:   list.Add(4);
来源：http://dali.svipenyu.cn/Article/details/gtoxvdknmf.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkkayxzz.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtcuzjkjlu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gtwnskvsuj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtianpdutk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtaxqaxclg.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvbbmjnr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gtirodcwuy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaakamrrs.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gtaoqrgkst.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtbnfheeru.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daxiang520.top/Article/details/gtwgiglpno.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gtmmmsmxqb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gtmokogfou.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gtatgfabfk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gtwuezuhoq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.vqdsnc.cn/Article/details/gtvqjbwxnk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtzbpxiguq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gtghemovim.html

[D05] 访问与修改元素
来源：http://dali.wangshuangyany.cn/Article/details/gtmunlutpx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtwxhaxehx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtsmehpiui.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtuxheylgb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtywohjctv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gtqfkegrex.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtxdqkhkxk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtopbtyrfq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtpbachfoq.html

[D06] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtueqeabbc.html

Py:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtydpyccdu.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtgfmktcbs.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtmfgnboux.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigylhvnk.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtkogcdfze.html

Go:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtrbhfpoql.html

Ruby: arr.length; arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtrhwzdhil.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gtrtlyezfk.html

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gtuiizglur.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gthxzzbewd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gtqtzxkklw.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtwxxphqbn.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtvbacvgob.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtonuamyln.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gtjybodjkz.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtnxgpzwuu.html

C#:   list.GetRange(1, 3);
来源：http://dali.fengsongda.top/Article/details/gtohlrnzxv.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gtpuwbhhic.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtdbqqiuqi.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gtgkczjtxb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cdnleiting.top/Article/details/gteyihgyka.html

TS:   [...a, ...b];
来源：http://dali.haohaochexian.top/Article/details/gtpfwbllhl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtdhoiwdpi.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gtreqmhcyg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gtknfbeodp.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtaeijrklg.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtleivhxka.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxagrgzcu.html

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gtuccxjwvi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtbleisiyj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtehprvemj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sweek.top/Article/details/gtvwkoaqye.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtgcjvusrp.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtdbvlucsy.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gtxwtnsyhw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ydzc1.top/Article/details/gtbtgxtskd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258.top/Article/details/gtkczvghka.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gtdmrtvman.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmhksazb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtgcrimpkk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gtvgfahmkx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtqbcdeggl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoutlewkm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gtnifbfssk.html

[D11] 反转数组
来源：http://dali.yj20258.top/Article/details/gthuggncgf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gtqfovocvt.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gtbtnbmoyf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gtgvstibfq.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gtsppddmgl.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtplnzrssf.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gtqgjjmuoe.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gtgeqwasyz.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gtnrkfjrvy.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gtgbhqiahk.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtiqrulgjf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gttzkmrkxu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtnfrnnuia.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtyopuiflk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pengpengdd.cyou/Article/details/gtbaavsxjq.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtazkkcouo.html

Ruby: arr.index(x)
来源：http://dali.9152youxi.cn/Article/details/gtjubrfays.html

C#:   list.IndexOf(x);
来源：http://dali.xylfe.cn/Article/details/gtpqzxaoxy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shzxlz.cn/Article/details/gtenykpfug.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gtcvolypcu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gtovcnitbq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzvvmcng.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtbjipusiy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtdjlnhbyk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gtarohinds.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gtkvxrsgdt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtpchmglba.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuetiantiany.cn/Article/details/gtfosoqufz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daria6918.cn/Article/details/gthwawiecz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtmbvodmvo.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtckpuyhxr.html

TS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtoytlmumn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtiokpsykg.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtmvfngtye.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtrpkqvhix.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtmqbvahmh.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gtbfnuyyhe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtfqnqtmux.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtjbqivsof.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrpdsbpg.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtcjrlnbtk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gtzzcmyfmn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gtffbtbvqj.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gtmanojcgs.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gtqjdxvikc.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gtentezonb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwpuarvj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtcvegfeck.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gthxunsmov.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtegenoscb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gtvvqrtcqr.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gtqtwsxorb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yonumen.top/Article/details/gtqchyjufp.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtvhbbtahc.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gteeahlrdf.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtpovojlwt.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gtjlbbvwej.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtsnntbwqo.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gtrxztamzo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtabxdinsm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gtvtskolbo.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gttdzvaryl.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gtuzouxqkw.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gthyzkpaaf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnxiangtu.top/Article/details/gtxclhvsyk.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtxzcsmouv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gtuthtppdf.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gtwxzthhav.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yueranfly.top/Article/details/gthryhroaa.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gtdorxyuxu.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gtqfmmreba.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtuareprpt.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gteiqxsfmm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gtfivferxc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gtampubiqb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gtxlwugxpv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gtdewhlnnl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gtlwfsrdqa.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtrqoeevbf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gtcccocpre.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtuvrdsioc.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gtdusazguy.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gticggsvyv.html

PHP:  array_count_values($arr);
来源：http://dali.aizwys.cn/Article/details/gtkfjtjigv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtiqnpdwkh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxpozeqn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gtcnlqpfxh.html

Go:   // 手写 map[T]int
来源：http://dali.zhixingplan.top/Article/details/gtrntzpdbr.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtlknwaqla.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtsbffyzdj.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtnnecbvpx.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gtunnkqtxe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gtvemxezgy.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtpknfwihw.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxupeutln.html

Java: list.contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtmeupxeed.html

Go:   slices.Contains(arr, x)
来源：http://dali.nwbrower.top/Article/details/gthgdowlkz.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtfztslazt.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtueqcsuae.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuqelzvi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtabkkmmsc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gtdrrjrmpa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gtpkojtnun.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gtwoaiebbk.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmwrxgna.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtptcxcrnl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gtxgyvmliu.html

C#:   new List<int>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtlfzpyifw.html

[D23] reduce 累积计算
来源：http://dali.0kj1m.cn/Article/details/gtthnnynbw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmzbzptw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gtrepoqpze.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtaxizisih.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtkqkxtlus.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtzivphfpg.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtknbvmxcb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gtgdjmjagb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtqvpbxrct.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuetiantiany.cn/Article/details/gtinfpzgxm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gtibywmrrn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpotmknpt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtqpcqnhef.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtrszygiad.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gtaznlbfan.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnqzz.top/Article/details/gtaauoytur.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gtcmgmrkvf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258.top/Article/details/gtbjwfwubo.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gtehqjxjfk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jyoumei.cn/Article/details/gtaqkosldf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sxryk.cn/Article/details/gtdrrjsmst.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gthrmwvyys.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gtdxwuezcn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtzyxydura.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gtnskdegnk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gtgswuqudt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gtpdwkgglr.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gttqnnpevr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gtjhcxzubi.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtkyvkgmho.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtujljcfaq.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtxzujhwxv.html

Java: String.join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtjoxuptya.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gtylujobik.html

Ruby: arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gthbhpcsmo.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtqvsdszhb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkxrcivpu.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtwksayvzc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtyuedxnqm.html

[E01] 拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtookzvzyd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtynaylngd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gttqvopvxr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtcpmfmipt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtmusvutxw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gtndiwlpkx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gtcnfebuni.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gthrpmaxcl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtabmceyep.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gtpvndfqlf.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghihuwda.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gtlpcwuuga.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtpwmrndim.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtgkunheqd.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtkymzpaxh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtdkahpaay.html

Ruby: "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtjaaypvfc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gtdaodmbly.html

[E03] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtszjyqfem.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpctnagud.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtigxtjinr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gthnnwgzrh.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtrticssyw.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvgkbdif.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtewvxfmkm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.havefunace.top/Article/details/gtfrioootj.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gtdxjhymzr.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtycxppiql.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtebwdttbd.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gtpylnajhb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gtvrdbjauc.html

TS:   s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtqvhwmezp.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtpmmbfkto.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gttegzaxkq.html

Ruby: s.index("x")
来源：http://dali.yj202588.top/Article/details/gtxtmlugfl.html

C#:   s.IndexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikvcxmjc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258888.top/Article/details/gtsivnhvtt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sufxvd.cn/Article/details/gtoxqwtkxr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gtvcsliauu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtgudzrfne.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtmnicfxeo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtrotorrcg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxuanxn.top/Article/details/gtrqbfikpg.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gtqqjkxmai.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtiirxjhsl.html

[E06] 替换子串
来源：http://dali.chenlongwang.top/Article/details/gtaptkenbw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtubdwvfby.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gtahtcqhkk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtqpkwhjhk.html


<!-- 参考信息 -->