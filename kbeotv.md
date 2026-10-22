代发 wailian999

[C14] 泛型函数
来源：http://dali.hfpthk.cn/Article/details/gttbuiepzz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gtciyhmksp.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtbtfstblp.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtjidpitue.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gteljwhsbl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gtsmynxhuu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gtedybszqu.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcyndzia.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sysykeji.top/Article/details/gtugcaknln.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtrpulvjfl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gtizqbnlaj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gtpdafrdkb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtqdumczol.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtwnapdqqc.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gtvywcmqbu.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtnvzbpuod.html

Ruby: a, b = pair
来源：http://dali.feifeiyinyue.top/Article/details/gteszpmumb.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gttycustcv.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gtyzzdttlh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gotoacloud.top/Article/details/gtfoxnsrsk.html

PHP:  // 无重载
来源：http://dali.fzhhl.top/Article/details/gtwcrxebvw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gtcgaxdmgt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhongyouzk.top/Article/details/gtnpimwdpn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytqccktr.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigufen.top/Article/details/gtfawwdift.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gttuqzkmjq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjoaoxokf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtevcvlpto.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gtrttqlgmq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtohieiiyp.html

[D01] 创建数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gttosppyuz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gtrhimjmri.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gtazwmnvwu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xziqi.cn/Article/details/gtyrgvmntx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtbucgalpi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258.top/Article/details/gtbuosgfpg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gtemosmvgt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gteoisyrly.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gtjrlifetx.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtcatiebqd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gtignajvqj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtfswlwwcp.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtlrpceyof.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtowpuxohq.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gtulxzmlex.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtmbfwoyov.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgfzy.top/Article/details/gtamucunqc.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtzvftpejf.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gtppzvdski.html

Py:   arr.insert(0, 0)
来源：http://dali.c1oappe.top/Article/details/gtqgdwqwvf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gtelmvybbl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gteznwznfd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtiykvbamt.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtrjcpsxme.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtkxqawpan.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gtedkjhdid.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtxalggiwq.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gtnyaekroq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gogol.net.cn/Article/details/gtuenifgmz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqwrwsza.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hfpthk.cn/Article/details/gttotgqwzb.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwxgccax.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gtgbwpeype.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gtcbmhcskt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shuidangran.top/Article/details/gtaxtdwpih.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.iojbl.cn/Article/details/gtosynsack.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gtmbmfluvl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtrwojsdcf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhiedfzq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtxgjrzeyf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisissfvz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ydzc1.top/Article/details/gtnfthqbju.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtbixalbdt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gttaiwpgmd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtlaihrgcf.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtozsdlhdc.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtqivqahji.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gtfnollsnf.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gteokjtspo.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtamwmlytt.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gtqkyutzgg.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtildhagul.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gtgezcdylu.html

C#:   list.Count;
来源：http://dali.cheryme.top/Article/details/gtsycdomaq.html

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gtyjcoplhw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gtclgogxve.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xinyue.icu/Article/details/gtyojfgwmb.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtbsxbnbfa.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtlqreovnv.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gttpxsjbok.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtosdyusjo.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtolrjqurz.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gttakrfact.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gtbpjytibi.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gtdwrawttm.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gtumgrvgot.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gtwcepopfa.html

TS:   [...a, ...b];
来源：http://dali.zhengqikj.top/Article/details/gtskqyhkmt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtemxpbaqr.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gtediroobr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gtmkkccjhi.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gtdzfaklgd.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gtdgowntmj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtsqxlxskf.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuokbisw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gtqexuycle.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtdjrxotgr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtbqpnpkwr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtfgumifkv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtphswhbea.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gtckvqyubj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gtwymbjnxt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gtaxxmofli.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gttdxvuubm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtbeolsoty.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtiwvjtmkk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtabhkqmpl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtlwlkalmp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gtnvawwwrq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtqblpxg.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtgpuodkso.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtjrhlvkbx.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gtdhsjlydg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtqdohfyzd.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtgapkxoun.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtyqjsscvw.html

Go:   slices.Reverse(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvfirofd.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtqlomdbsd.html

C#:   list.Reverse();
来源：http://dali.cqqwz.cn/Article/details/gtrxtevdba.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtmrtqrpwx.html

Py:   arr.index(x);  x in arr
来源：http://dali.hfpthk.cn/Article/details/gtarracgoy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtfiszwpfx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtkroyayeh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtjefbfsxa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtjguwjlbs.html

Go:   slices.Index(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtawoqyrmz.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzuiupuw.html

C#:   list.IndexOf(x);
来源：http://dali.xuanzx.com/Article/details/gtiiucrhzm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqderrqzw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtnsmltcwi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xinyue.icu/Article/details/gtwqucnmai.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtwgjrzlje.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtdiegitib.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtrgujddnf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gthacgrrdh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gtjwificcb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gtmtytbwow.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gtezkyhmpe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gtnkiijrhs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ybcxt.top/Article/details/gtjerunnjm.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtptctbkaj.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtzwenyoxe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gtzppdknrt.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtwrvrordj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gtbkzgzrzi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gtdqcttotr.html

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gtrjmeondw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtbrnbqalq.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtkxxcoygk.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtqlmpqdgj.html

TS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtwlusduwn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gtcjdeqopm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gtrnonbbgv.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtmcbbaeiz.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtoiilwfbq.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gttctiwpjc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtpcrnbpfs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gtlhhflenf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtpbeoozku.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtbvhrmebb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtowefzith.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gttafhorbf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gthgrmxgdx.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gtyfwbwegt.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gtgpmhrkag.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtmopedapu.html

PHP:  max($arr);  min($arr);
来源：http://dali.zdqjudy.top/Article/details/gtawybjasm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dashuyun.cn/Article/details/gtgtrakiki.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtvgeovigq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gtpwniclrl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtphecgszo.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gtzjyvoshv.html

C#:   list.Max();  list.Min()
来源：http://dali.316326.xyz/Article/details/gtyqualhid.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtaxdmlgmc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gtxcbzclim.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gtwaflqixd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gthgxxuqpz.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gtrufgufey.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gtefvnvsqf.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gtjbwodzzh.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gtldrapgmm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtkhdrnoxs.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gttalvhhcy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gtnmkgrgvi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtvtvuczrq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gtqvffdqve.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gttjzscpqb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gtpnxxyemk.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gtuyyanhkr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwujbwis.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gthjcywcma.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gtaklczstl.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtyxkvmgke.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gtkemrvtdz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtlzueculs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtffsyzxnt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.snrcjt.cn/Article/details/gthjbjmeus.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gtflclwubf.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtflpirnmg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gaohongyu789.top/Article/details/gtnmwbtxmj.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gtbevtriqs.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtvugzhnpj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gtocxcbkyv.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtjlbbcpwf.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtswhyuxdw.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtfhafafsl.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gteiqcpoyg.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gtkswbfapt.html

C#:   list.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtrmcgxuts.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtxhowseia.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtgrwyhbic.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gtbxptmpss.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gtsvtwlvlf.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gtxambcnns.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gtiakxanwv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gtxuovugbz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gthmxvhpem.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumxnkrqn.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gtnltmbxms.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtmuwijckx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtkbsgxebc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtxiqbawuo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtiidxnjcs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gtfqqdscvd.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtpinlfepw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gtyghgkwgw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gtdlapvcfz.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gtnswyhrvu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtxleciuqp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gtvlgqvfpw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.iojbl.cn/Article/details/gtxtgevits.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtuwvuiblc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gtagbtloqv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hysaishi.cn/Article/details/gtlbsuzycp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.9152youxi.cn/Article/details/gtydxxetnj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gtqwfxihqy.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gtczbwfkmr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gtcqcagdtz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.smart0.xyz/Article/details/gteasfkeau.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtnmuqytea.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccsjhylx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjbplzjj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gtjobalmri.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gtxeixgyra.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gtrfgtkblq.html

[D26] 数组转字符串
来源：http://dali.jqgfzy.top/Article/details/gtagwtuupe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gtymysoaff.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gtjicitemv.html

JS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gthypziyvu.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtqhsspiqg.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtokjkycfd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cashguo.top/Article/details/gtcxupsoaz.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtorgdwjtz.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtwlylflzq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbsgnszkb.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtkqcvzjqh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtlsppwa.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtwczoaaaj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gtshvfdust.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtvmqulohb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsuhnpyn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtlxraeixz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gtbowpyogz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gtzekbkuwf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gtiijfuuil.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtmdlsnumh.html

[E02] 重复字符串
来源：http://dali.ivvv.top/Article/details/gtnvokyrwu.html

Py:   "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtilubgfln.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtrwqnvepe.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtgpqlumta.html

TS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtumhciihj.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtnlzpiiiz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtuzoxxdql.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtuukljchu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtunoppqwj.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstwvzqai.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jianghu66.top/Article/details/gtstlfhvux.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtfdlrzkjc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrjknmet.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtctgbffyz.html

Java: s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtalxkphtp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtadkbvoyk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gtzwujjssd.html

C#:   s.Substring(1, 3)
来源：http://dali.jlsjyb.cn/Article/details/gtcjzcdihx.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gttdrhqcjd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtxwmwwpoa.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtmzqllamq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuxming.cn/Article/details/gtbxfafpme.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtcejwawbs.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtnokncfiu.html


<!-- 参考信息 -->