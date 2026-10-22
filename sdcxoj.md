代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yueranfly.top/Article/details/gtkcwdrgyc.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gtzpyvidil.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtwxcdkzzq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtsjefncun.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrszmdnmc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtzxrlckxh.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gtuyfurpsl.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtuciywptq.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gtylkyqjoa.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gtsayvyoml.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gtjvsykmdd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gtkxbyrdyk.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gtnmkbcyur.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gthbycvjvg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtxvewufhm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbpioqhy.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuanzx.com/Article/details/gtqaogwjvj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jiagoushi.top/Article/details/gtzkxrpfls.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtszecjjat.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnxgbsvmi.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gtvlhlwpig.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbstuthql.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtoarfasoz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gtuqdrojle.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtsgbqwslk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtvvqkucrb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtsyvhfqtk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.andypj.xyz/Article/details/gtgiilnctm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gtrjefmcfy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gttcjifunr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gttzsbvqyz.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gttpjddxgx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuxming.cn/Article/details/gtnpmyjlyd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jianghu66.top/Article/details/gtdihxitln.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtvhywdjmn.html

TS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtujzscztp.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtiliyrtde.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtxqcmwjhp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gtfxenoxjx.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthorfxlwe.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gtwazcghnh.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtokcgxutg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gttoqhhlab.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gtceaytsuw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtdtqsnwjs.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtwwvyabzd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sxryk.cn/Article/details/gtxtjvbwxq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gtdpkgzgfa.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtaolypfuq.html

[D04] 删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtfsonjvjn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtqitraqlk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gticszjkud.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yangfankeji.com/Article/details/gtpiptatbf.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gtauspgrzs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gtwyglraqr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtualqgqds.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sysykeji.top/Article/details/gtrpdjmomw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gtvymawyno.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtvnpyshgu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtlhrpzjpt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtvmmqcqqg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gthavovbie.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gteqdaboxi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.316326.xyz/Article/details/gtqafbibpb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtfmjuoxkk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtzshgfekc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtjgzlykae.html

[D06] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtopjgbdif.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtfdeykczt.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtfllfkrnp.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtgjirutsk.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtmkxnjezq.html

Java: list.size();
来源：http://dali.jinqigufen.top/Article/details/gtetmebaet.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtnrwgowyq.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gttfathyrs.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuulknzyd.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gtwuwklnuy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ydzc1.top/Article/details/gtagagjkqq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yvedp.cn/Article/details/gtbgpkxpcb.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtxriskfjd.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtwfetwbva.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtcytrmjze.html

Go:   arr[1:4]
来源：http://dali.havefunace.top/Article/details/gtcftislcm.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gteqjowhgu.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gtdeaqmhtk.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gtavygwxmg.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gtftpyomjo.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gthyudnsto.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gtyuqhskzv.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcegqhbmq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.mhx1999.top/Article/details/gtqdjyiwrx.html

Go:   append(a, b...)
来源：http://dali.hysaishi.cn/Article/details/gtaipfnpah.html

Ruby: a + b;  a.concat(b)
来源：http://dali.mhx1999.top/Article/details/gtlljdqioj.html

C#:   a.Concat(b).ToList()
来源：http://dali.bjfxy.top/Article/details/gtnbytrqos.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gtfhnjknrw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtjtderphc.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtbtvcsnwl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gtiabtyofh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gtdsgyrlse.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gtmghcmuhp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtiidveswv.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtmvirhvlg.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gtjhzdqsoi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gtnuipfjid.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gtxhiwuxkp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtjdlepjul.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtwjkjeejw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcfhatns.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gtnntuewcs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gtrsjdgjyl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtompnxrqj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gtfkgmnjox.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtozqgmwim.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtrslybfbl.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gtarkutnvf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gtixemmfkf.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gtdmidisez.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gttzxofvkq.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gtbjeyakxq.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtynvvyopo.html

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gtdnvpxxiq.html

[D12] 查找元素下标
来源：http://dali.daria6918.cn/Article/details/gtkzuirqal.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacbhjswh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtccqdyigs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtngscvhww.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtwahoiagx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ppjwa.cn/Article/details/gtentdgogj.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtkkpvyocu.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gtrdzqwamv.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gtrwcyovlv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gteriwwysn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gtpwupyyqo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gaohongyu789.top/Article/details/gtbmxptcny.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtjnwqvnls.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbjvtxuo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtejuqtzeu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gtfxakrgfh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gtehgwtdtl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtiprinkdk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gtawgjzizf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtqsyjigwc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtefdtyikc.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjssjpsh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtoovnpmbn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guannengcc.top/Article/details/gtyrwrfxko.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtjkuhgkdd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtrmeghicn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtbhymzkip.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtgqcipjsf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtzzvhpqoh.html

PHP:  array_unique($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtjtnczxlw.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtcxezlyva.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtuyhpnebn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenjidiqi.icu/Article/details/gtmvhfxsdj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gtpzjipgos.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohppzofc.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtolbpehwp.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gtiuuepirf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gtywdcgwac.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gtycqedmon.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gteoryhshv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtmgdmhfvu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtwbpyum.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gtjcbnpvpz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gtqnbzppgv.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gthffeiwiy.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gtygodnwed.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gtgdrtnhjs.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlivgghxb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtkctrnzfb.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtnjzmncxi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ivvv.top/Article/details/gtnmkzvsaz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gtltcbtfkk.html

Ruby: arr.max;  arr.min
来源：http://dali.sysykeji.top/Article/details/gtiufsdbqk.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtzbsazvyq.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtmzekzblm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gtqyinymwj.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtxjbkzkzr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gtpylogmdo.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthinuxkhg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gteubptbul.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gthtnwvthq.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gtgsochzmv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gtngykkuuj.html

[D19] 按字段分组
来源：http://dali.jyoumei.cn/Article/details/gtdjagohqs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gtzntuqopb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtecpoagcs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtvzullesa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtkdlkksmh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gtlliotjdx.html

Go:   // 手写 map[string][]T
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuapbgvjn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gtcmwkviqw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgalrvgtt.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gtvafzbowm.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtjmlbhinf.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gtrvhfacmn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtnuhjatgv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtphaniugl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gthqaxhgav.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gtnllgoaak.html

Ruby: arr.tally
来源：http://dali.gzhubu.top/Article/details/gtnrlmvrmc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gtgugkzqvb.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtkdenjlcb.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtfuyvrxgl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gtxmdoaats.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtprsqfogi.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gtdgawxypg.html

Java: list.contains(x)
来源：http://dali.cheryme.top/Article/details/gtzkcutxvh.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtnxoeyofq.html

Ruby: arr.include?(x)
来源：http://dali.snrcjt.cn/Article/details/gtrwbnojuu.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtmsksvucq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtiovfsltw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gtpkmvbjuz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gtgaordbbb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gttyisdzxf.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gthotksjcf.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxozbtva.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtqwtabmba.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtmcosaoik.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gtkspuiwqh.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtoxqxpwak.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gtjhmngcol.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gtszasllag.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtbtltjqxk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtmtjymibl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gtctehdqux.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtjduauyiy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gtpxbiisez.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cdnleiting.top/Article/details/gtyhfpjskm.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gtwmecjicu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gzhubu.top/Article/details/gtnidiglaw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gtztuhlvzi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gtnjnxhuuo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gtktscrosu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtbwgsmhrz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gtaunrgvqg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gtpvlrlhnk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gtyonxztwn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhoulong.xyz/Article/details/gthvoyiltj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gtqyilkbei.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxuanxn.top/Article/details/gtwaasqlmw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gtjhdlpmgl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtopqqqjyw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtsnbiwziz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gtyazgqfti.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktpgyqan.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gthocoibpg.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gtxwbtpqiz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gtbqhiybfo.html

PHP:  implode(", ", $arr);
来源：http://dali.pycfn.com/Article/details/gtdaejbuvl.html

JS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtrroqxvdp.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtbbmaxdcg.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtufxqapjk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtunukvbis.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gthvgmdqce.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtddghtcpd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkqsmpqyb.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gtlbmmciuu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoabajcue.html

[E01] 拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtbbwjgkhm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gthhqgddoc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gtdnownneb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtbaesaaoo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gtzdcwiavm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yueranfly.top/Article/details/gtqoxptsap.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gtwndyiilq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gtfvdyfwdm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtwlrjqejr.html

[E02] 重复字符串
来源：http://dali.tanke756.top/Article/details/gtxbumhhxe.html

Py:   "ab" * 3
来源：http://dali.cqqwz.cn/Article/details/gtedvbjvnl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyrqgimw.html

JS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtbhohobea.html

TS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtdxewsgyu.html

Java: "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtfrcfxbee.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gtoxpjtcwy.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtlrrfukdx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gtwngtemdj.html

[E03] 截取子串
来源：http://dali.yj20258.top/Article/details/gtvlvxjedz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigfzy.top/Article/details/gtifegdjos.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gthabghgdp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtztcxybcm.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gtzcrtkdla.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtizbqeudp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenzaomai.com/Article/details/gtmjcwmzjq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtjnqpkavh.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtuoyghkga.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gtrfqhifck.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtypmreosi.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gtqrwbwwwi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cucudq.cn/Article/details/gtawuheebz.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gthqbnkbvu.html

Java: s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtfkoapqor.html

Go:   strings.Index(s, "x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfdsaicq.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbckuayei.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtwpfrrhvk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwbcbnmi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtfdcsmmfg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gtdidksxus.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtyvwmfyuc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gtsflnctvf.html


<!-- 参考信息 -->