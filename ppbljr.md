代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gt2sihacouf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qfbsybwd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ripdzywc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2jhkwjkox.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2ifntjnim.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gt2mpmcrawv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgcgsfwl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pccmtulk.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrcqfgrk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gt2oixmzihj.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbnzztxx.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2vnqoojol.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzkucwjk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2svmrzkss.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shzxlz.cn/Article/details/gt2niaicmli.html

Ruby: # 无泛型
来源：http://dali.ppjwa.cn/Article/details/gt2hrpihfxz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gt2qjhqlgrp.html

[C15] 解构 / 展开参数
来源：http://dali.jqgufenzy.top/Article/details/gt2rvvumfzp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gt2oihmbkix.html

PHP:  [$a, $b] = $pair;
来源：http://dali.vqdsnc.cn/Article/details/gt2ipgzfsla.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gt2fbdjtbyx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2npeckxem.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2ncedhzqf.html

Go:   // 无解构
来源：http://dali.shzxlz.cn/Article/details/gt2ocdtsqks.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gt2tffmwkrb.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gt2sfbbrvkg.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gt2xummbqhe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eexlrwvw.html

PHP:  // 无重载
来源：http://dali.c1oappe.top/Article/details/gt2qorzjqmd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gt2kgiwqzwy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cashguo.top/Article/details/gt2nzmzijmm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gt2qcvzdfkx.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gt2vdcpxmsh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpvpvwww.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ipmrvbjg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jntxphhx.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gt2qygcunsu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2mjnxjygv.html

[D01] 创建数组 / 列表
来源：http://dali.kuanghao11.cn/Article/details/gt2tsgtzckk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gt2tvnsjbys.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gt2wlxxgfkb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2hahtjkfd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gt2xuynuhwl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esdkxtqx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gt2hyrncooj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gt2zrsbqqwu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gt2hkouyrnl.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gt2biceenia.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gt2kxwtwrpx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2picngeii.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gt2jqgpedez.html

TS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2urtgblyu.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2aczmyacg.html

Go:   arr = append(arr, 4)
来源：http://dali.hnqzz.top/Article/details/gt2tfqonhrg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gt2moyazcqz.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2oigdhibu.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmwovcdj.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gt2clsqxyax.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gt2rigeluno.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gt2eqmjjulo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2etvgewsy.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfzslejc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gt2pzphpfrl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nwbrower.top/Article/details/gt2gqhqwxrh.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2pezzmlff.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gt2pghqoldm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gt2odwcnoed.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gt2mputqzbf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsazicwm.html

TS:   arr.splice(0, 1);
来源：http://dali.snrcjt.cn/Article/details/gt2ujmtisht.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xinyue.icu/Article/details/gt2fjmzbxdz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdaynepr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gt2mawqwexv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigufen.top/Article/details/gt2dbunpnes.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gt2etiehupx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xromgjha.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gt2nuqkplso.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gt2pwzjgdux.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atfxexkc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gt2zpoluzcn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2mncdoowg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2wadwztyl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2vpyblxye.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gt2tndjtvsy.html

Py:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2tpnwuuhf.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gt2zavhnklh.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyikbuyk.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gt2otlewttb.html

Java: list.size();
来源：http://dali.jianghu66.top/Article/details/gt2bjmgfcjy.html

Go:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2mxynrasu.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gt2grmnqaqc.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gt2mddrrmoy.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gt2bzdktqzk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gt2gyythaxu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htegqiuv.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2xkbyxkbv.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2dptwoocg.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2nwscbynu.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqxpuzqu.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gt2wqnqlxrv.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gt2sgzenlkk.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gt2bndljkof.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2waczifmv.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gt2jtvfxwri.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gt2gzcaantm.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gt2kvxfjapm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gthqgmvm.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gt2nahpbrvn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gt2pfficitk.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2eosmuhil.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gt2ltiolxil.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gt2phkuilwh.html

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gt2jyuzvusq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dashuyun.cn/Article/details/gt2nzltaush.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gt2modugrcc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ppjwa.cn/Article/details/gt2bjrxjkby.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2wlqpborh.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gt2zpmfntkq.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gt2wwpcbdae.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gt2wtmmvykn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gt2ekbqmcli.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gt2brtulikp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxgjulbr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lntazqyw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptpcbazx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzrdiwia.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gt2iintwxom.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gt2dljkzslt.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gt2nutzoezo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ogbwzarn.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hfoscmxq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ppjwa.cn/Article/details/gt2smivbjjv.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gt2uatnheig.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhmgffqo.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gt2hewcfuqr.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gt2xvclvmzc.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2ugtjeszl.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gt2udimmvlg.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gt2eobptyzi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2kjoumfpy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2eaznikye.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gt2lxqehufh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpddlskm.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2oyvsoxgt.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2trswokxi.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gt2smcverar.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gt2iigkxure.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gt2aeurubpb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fengsongda.top/Article/details/gt2basqwqmx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gt2cxljurlo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gt2jtxtwfat.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gt2oxotzokl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gt2sterdkkp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dolziezd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2juxpttdd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gt2jftfsvzw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hammf.cn/Article/details/gt2fxlfcnun.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2lzidmbdp.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gt2rxipzfax.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2gipoihlv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gt2csqcipkc.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzsuamcu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2tckjssyh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2rqftmvwq.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2htheyuqn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gt2lvesndea.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnilylct.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2uoxiuzgw.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2rbghvrzp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.iojbl.cn/Article/details/gt2wyamjyid.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gt2yncpiaxn.html

Ruby: arr.uniq
来源：http://dali.fzhhl.top/Article/details/gt2xjihkdcu.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2fwawttzj.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gt2txpkxzhg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2catcrxlw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gt2ivdlcbiy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2akbqddge.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2rqddmksz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gt2pasdbuiy.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbdxgnqc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gt2mstltalf.html

C#:   list.Sum();  list.Average()
来源：http://dali.andypj.xyz/Article/details/gt2cpyonhmz.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gt2gaahqxsl.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gt2pvgnifjr.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2mqsrbjcv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gt2pdcedclm.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gt2keenxuto.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gt2znujlmhx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2meqcgcmc.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzpsufyp.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgfyybaf.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gt2nvrcoank.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khcqewty.html

PHP:  array_merge(...$nested);
来源：http://dali.yangfankeji.com/Article/details/gt2atcejyrw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvfgmzcy.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gt2iotchikq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gt2apoziork.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gt2hxwlfnii.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gt2xcejhkuo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2gdatntas.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gt2irxhrdmh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jiagoushi.top/Article/details/gt2yhissmjm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gt2caohmokz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cdnleiting.top/Article/details/gt2vasgkzny.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gt2isihbygj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gt2njuuxrzd.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gt2cmefvota.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gt2fliuklhj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gt2rsterpvz.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gt2pdygpusv.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2bwkbclxs.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2kkhtaonl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gt2toobsnes.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gt2kkevqkhz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shuidangran.top/Article/details/gt2xmrmuyzt.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gt2cddterrn.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gt2vdcenuht.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gt2epgykvqe.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gt2zfkegbng.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gt2ryiuxptc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gt2mxcqozlw.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2hbdrgtgt.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2vxvfphsw.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2tsrsmbxd.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2cyqnhdlu.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gt2zgffflgu.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nucsdxom.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gt2auenuypy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gzhubu.top/Article/details/gt2vlldohpm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zycfv.cn/Article/details/gt2nubmqxbn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2zwnyxdii.html

TS:   [...arr];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgyejvul.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gt2zecmhexw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gt2pefokkal.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gt2asydteso.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gt2awyhmmsh.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwwhppoc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gt2gvudkqah.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2fpgtplme.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gt2ogbftqmo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2komakmlk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yueranfly.top/Article/details/gt2kaqepzil.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gt2dsdabynx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gt2pbycewwn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gt2ogepddbk.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuxming.cn/Article/details/gt2hsmvgvpf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2imwxhaon.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xziqi.cn/Article/details/gt2hvzgcdwg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahgqyuom.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2iievkidr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gt2wktogdde.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gt2oqnqskci.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gotoacloud.top/Article/details/gt2rhlevgrm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gt2xgktinzj.html

[D25] Set 集合去重与交并差
来源：http://dali.tianlin.xyz/Article/details/gt2uetxbudl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnhlaerb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gt2hlqgnksu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkigoijw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gt2jhhqnngr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2lznixokm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gt2psorfnxc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sweek.top/Article/details/gt2wbgecvas.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gt2zdskcuoi.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gt2oghiocim.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gt2cyybpakg.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gt2yrdzomex.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gt2namdugfg.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2vgakjiff.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gt2izudrbfm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gt2rrhnqvxw.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2kplcltyp.html

C#:   string.Join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gt2dfobikry.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2jptgbrtt.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gt2yairwtqd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2bhhyjcxy.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gt2pnztwlgl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhixingplan.top/Article/details/gt2ycjiujek.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2exewjpqo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gt2vafzlzhm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gt2scmftcdt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258.top/Article/details/gt2lbcefhdt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gt2obotmqtp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gt2enpcvgub.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2jfiqriez.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gt2lsrnlmuh.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2ueadostl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gt2lopqavci.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgnldjrp.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2rzurduqi.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gt2jhrrkzcr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gt2ifhosils.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gt2rdiaistn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gt2xmxppwdx.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gt2upzyznxf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gt2gwzfioox.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2rmwfwwft.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2hufphzoo.html

TS:   s.slice(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qitrikko.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2ybalshmt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2uwdzwlwh.html


<!-- 参考信息 -->