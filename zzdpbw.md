代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gtojeeyaqz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nwbrower.top/Article/details/gtczzflurm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gtoidravpd.html

Ruby: # 无泛型
来源：http://dali.tian-w.cn/Article/details/gtgatzrqyy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbgvylnb.html

[C15] 解构 / 展开参数
来源：http://dali.nanxuanxn.top/Article/details/gtksvwvuvp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gttrsgclyp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gtwhwsoumn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtduhbmpgq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngrulboj.html

Java: // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtzldptkni.html

Go:   // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtosvupxiv.html

Ruby: a, b = pair
来源：http://dali.havefunace.top/Article/details/gthcarnhjy.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtmezegzca.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gtuasvkcvr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gtmkaqhqii.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gtaaccqntz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yanxiufei.cn/Article/details/gtivzgmorh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gtcyocjxol.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gtojcgbtmr.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gtiflofuxv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sxryk.cn/Article/details/gttusppxem.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gthmaysget.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtcfmibpum.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigfzy.top/Article/details/gtjxigdzwy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdnlbyppa.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gttojrjhmr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gtxbrajiwr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gthqgolqcb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtkfqzkpyk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cqqwz.cn/Article/details/gtnlglafjb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuetiantiany.cn/Article/details/gtkxxhiodq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gtanbjposq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtcuooglfy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gtaifcyccf.html

[D02] 追加元素到末尾
来源：http://dali.9152youxi.cn/Article/details/gtsrdnfxgj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gtsgjjfrnc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gtnwlobnew.html

JS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtoinpeaew.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtkxgxpkbg.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtzxrtetlq.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gteyiqgyle.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtlmkqvhhk.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gthqayuhwm.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gtyaklxsdm.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gtkmjhsrqx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ppjwa.cn/Article/details/gtxybuvbol.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gtqbuhnxny.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gtlzsmrifv.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gthiuzzeil.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gtxqdfpcdb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gtbqjybrdv.html

C#:   list.Insert(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtgnjaticc.html

[D04] 删除元素
来源：http://dali.nanxuanxn.top/Article/details/gtgqvcpytp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gtncnumqoq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtrsqdjgve.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gtiaktiruy.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gtxwgdkihx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtflqezyze.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gtdzbfksyl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gtyvmedjuk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gtokuhifee.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtiuvwxqbf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtvbhdxbom.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtqnhwsyah.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtkyzclrkd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gtehgiipqp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gtfudknday.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtuuauoxnz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtkhmpjzjz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtifskqolb.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtelibsalf.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtkaurqehh.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtfewklvcx.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtcjnklzin.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtfecgadnt.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gtcxdhassp.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtogercuwv.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gtdllkkcvt.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gtrlgtarqj.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gtbqkycgrq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gtzviebgcm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gtdhnyeyhz.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtfcpeoqoq.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtthlauuxd.html

Java: list.subList(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtznuqhxla.html

Go:   arr[1:4]
来源：http://dali.iojbl.cn/Article/details/gtoznhxhcq.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gttxomfaqp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtheuxwqtd.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gtrbellbyh.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtcxfqvwjf.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtivahgwdh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gtkntofucv.html

TS:   [...a, ...b];
来源：http://dali.yongpay.top/Article/details/gtlwtkfxhs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtpsgxnvob.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gtyncziijz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gtnancsimv.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtygtrjglt.html

[D09] 排序（升序）
来源：http://dali.tianlin.xyz/Article/details/gtkizkdiol.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtnyqbmehb.html

PHP:  sort($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtxlusftql.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gtzdnsyfvb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtcjwmolwa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gtahwkrduv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtjtsfdkwq.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtzecgiiji.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvpeufkf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.316326.xyz/Article/details/gtuvdznyyr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtkdgbqbhr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gtrpplldcu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtnrbmtjfp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtxwgdgyyc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gthrzvxqas.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gotoacloud.top/Article/details/gteratvoqq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ehwqpu.com/Article/details/gtfxgkvvin.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtnynetjck.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gtemclzlub.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gtyqwckoui.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gtvkwmiiis.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtcxyexzxn.html

TS:   [...arr].reverse();
来源：http://dali.ivvv.top/Article/details/gtgcxzjnhb.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gtdawwsoge.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtlwdybbzk.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gtfygjfrbo.html

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gtjycfhqeo.html

[D12] 查找元素下标
来源：http://dali.mhx1999.top/Article/details/gtudjhsxqk.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gtedlvejmr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtdqpitssf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtlbzrlsiw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtgzzzmwcw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gtfhglxkbq.html

Go:   slices.Index(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtvasyqrek.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gtscaocpiu.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gtuzpnbcjh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtwdcaikra.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsulhvbj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtzzyagulc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtiubbduwk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtoeqtbcgq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shuidangran.top/Article/details/gtvjdmcvva.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gtfalebyxt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daxiang520.top/Article/details/gtlumlpmcs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjnghnxp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gtocrntkgc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gtrcoawuyq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtncjruucg.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtkszixtkp.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtbvwlvqgj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gtupzjwgqi.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtbnkcpsnn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtumkroftd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtxrknibkf.html

[D15] 去重
来源：http://dali.wangdashe.top/Article/details/gtarajzoaq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtchbdcqmv.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtaoalwdrh.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtwfzfbnet.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtypxxidyf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gtkayzfrzi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.316326.xyz/Article/details/gtjgjmjltw.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gtzfqjrpsz.html

C#:   list.Distinct().ToList()
来源：http://dali.hfpthk.cn/Article/details/gteajucusx.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gtnikvpnbd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtqdelfmtw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gtetjldiqu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtuifvgukp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtabjaxtnq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.havefunace.top/Article/details/gtwtrbtuoa.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gttqdkylhd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtmlmcfzug.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gtabugzxhm.html

[D17] 最大值与最小值
来源：http://dali.yanxiufei.cn/Article/details/gtvqakcgjj.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtevffozjz.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gtljfzbuag.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtithwydwj.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gtijaqxkqe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtwmbowiay.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtxzpchgql.html

Ruby: arr.max;  arr.min
来源：http://dali.gaohongyu789.top/Article/details/gtqwbkthfc.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gtczsfsnwa.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gtupgtbcoe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gtvpbayslk.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxuxpsgw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gthcutilbp.html

TS:   nested.flat();
来源：http://dali.ivvv.top/Article/details/gtkruokwkw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gtlemsthaz.html

Go:   // 手写双层循环
来源：http://dali.jiagoushi.top/Article/details/gtsmogjlkx.html

Ruby: nested.flatten
来源：http://dali.gotoacloud.top/Article/details/gtlhrgkcec.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gtwqulvmks.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gtzvwaksex.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gticnmtwve.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtkhpgwtrl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtovyrprra.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtcswnbkzv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ydzc1.top/Article/details/gtbgbdlgzr.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtjfhvgeuq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gtvqldxgch.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gthtmcncxc.html

[D20] 统计每个元素出现次数
来源：http://dali.iojbl.cn/Article/details/gtewngzdmr.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtrvvzurrx.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfhddcro.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtnfudyetx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvgbupjd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gtuffucnib.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gtnnzouosj.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gtqfnuiich.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gtfncbsyzk.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gtphjpoagm.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gtsyoemoqi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.iojbl.cn/Article/details/gtnxhacegb.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmthrwhib.html

TS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtomdociah.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtbjaogjqs.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtgcsntpbl.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtzptrdxyy.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gttwgmfoyw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gtuijtrrkg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gtgqxbbipy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guowangkeji.top/Article/details/gtjfyjtggx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjciytpjt.html

TS:   [...arr];
来源：http://dali.ehwqpu.com/Article/details/gtocxqmnth.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gtqapxakuk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqveenmqg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigfzy.top/Article/details/gtleapegaw.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxxatyrh.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gtoujqpgim.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuanzhike.top/Article/details/gtdsjucoyx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ppjwa.cn/Article/details/gtnupmeznq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtethdzexc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtmmqpnbyo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cucudq.cn/Article/details/gtldwzvplv.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtvwcxmzji.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gtobnffxrt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtzlqcqheb.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gtqjidgoim.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gtgfzxvxmh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jlsjyb.cn/Article/details/gtupntrmhg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtudgsqyzl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtuxijdvuu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtzuhsnjsb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gtguxmmguh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcwztkxe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yangfankeji.com/Article/details/gtqlekajwf.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gtgxnsmsmc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gttuwsxrmm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ydzc1.top/Article/details/gtsjblasao.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtjpvrqfvy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtqqgscafe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcnkqvpt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimpzsead.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtozxriudv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangdashe.top/Article/details/gtqvwyndze.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtxgrhkmij.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gtwqnwolii.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gtvhvxyqsw.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtwazncrrh.html

TS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtbtlmvgkv.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtfyfaeuyx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtbivmeejv.html

Ruby: arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtcahutftc.html

C#:   string.Join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtqnhucnbw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjhafscwd.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtrwlnubac.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqyoaebvl.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtntdtmzrc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gtvfktssap.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtawrirhps.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gtznejgeip.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuaawurvy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gtnpbnnllg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gtgdqbxjxd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangdashe.top/Article/details/gtcqjkvraj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gteelcavfm.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhyjnoxe.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtowjctbkg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gtmaqrutgi.html

JS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtxakzhwqx.html

TS:   "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtnnwnpsdv.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtmxjoupor.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gtusfeyfxb.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtjexlefuj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gtinogbhzu.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgfomlhw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlkiislz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtxemsnjhb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtsdemscom.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtthhzdvmj.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtojdgsrwh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ppjwa.cn/Article/details/gtavvgvbcm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gthulmhbud.html

C#:   s.Substring(1, 3)
来源：http://dali.birdmap.top/Article/details/gtaapstbod.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gteajljogq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtvazgcnzx.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gtogoyapgi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gtaznwefcl.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtfmxsetho.html

Java: s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gttxphbkjm.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gtsxqgpauz.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtxfxxrido.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtdihmdofa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gtlaqqduzo.html


<!-- 参考信息 -->