代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtkdhxfrny.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gtfiiuyhgu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gtldipedjm.html

Ruby: # 无泛型
来源：http://dali.yj202588.top/Article/details/gtxpmfkzgl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cashguo.top/Article/details/gtpqlswiqz.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtmxbtzfsj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gtwjobwbid.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gtvyvvcgsz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtmcxevltt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gtasthydyb.html

Java: // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gtqrvggwmm.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gtkahhpcpt.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gthvdhajov.html

C#:   var (a, b) = pair;
来源：http://dali.nanxuanxn.top/Article/details/gtttjeldot.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gtwavjvafz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtmfiudijz.html

PHP:  // 无重载
来源：http://dali.cashguo.top/Article/details/gtcfztcxns.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gttivylbhl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gtlcnipgsb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ivvv.top/Article/details/gtxcgocuxe.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gtojeablxd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtitiypfau.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gtyxuiwyhx.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gttyueqeif.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gtfavxmpxs.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtklfxmosc.html

[D01] 创建数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gthawrvzqe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gtlgbdmhuw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gtxddkkqco.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtirwzgqrd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gtmxeupdgt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gtwfagpoop.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gtaoibjnus.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtiqnhzvhe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gtkhotajve.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gtwtniipdt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gtsounrmoy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.quarkkingdee.top/Article/details/gtfhxunaap.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtokqrensp.html

TS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtpkxbwnuv.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gtmewuatrw.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtevoenvhx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gtlqlsuwus.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtjswybujo.html

[D03] 在指定位置插入元素
来源：http://dali.tanke756.top/Article/details/gtecchhqam.html

Py:   arr.insert(0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtbuathmhd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtakpkvgqm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gtyaujnbqd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtghsjmqnw.html

Java: list.add(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtcgtjusin.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtkwkipqnu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.bjfxy.top/Article/details/gtmmtnymse.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtjinebhbd.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gtmnbuvqix.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtdbhsnils.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gtisrrqlfx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtdhvdhyhb.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gtmdnwnske.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gtnmfasnez.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gtpznxjhhj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gthlecyeef.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gtywaqrubo.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtbnrmjgsh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtuqmxhlsx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsishcbvo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtkdvjzteg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hywenlv.cn/Article/details/gtahxukjhb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gtjylzdkxn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtupusnxmb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtkqsteehx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyaduxwh.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtrztpgkye.html

Py:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtbyodaatq.html

PHP:  count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtszovwjfr.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtzqsilkbc.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtktbajtkh.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gtrxrktzzg.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtnlxgvtpe.html

Ruby: arr.length; arr.size
来源：http://dali.9152youxi.cn/Article/details/gtxxcczotf.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gtzaumafwi.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gtgstiazwf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtkcfkwwyr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtyaaqfnfk.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtgulumglv.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtjginlugj.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtmlwxowzl.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gtsczptbng.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtnzftnejx.html

C#:   list.GetRange(1, 3);
来源：http://dali.fengsongda.top/Article/details/gtyxirvhvr.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gtyhccfezo.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtkumhmska.html

PHP:  array_merge($a, $b);
来源：http://dali.shzxlz.cn/Article/details/gtmistuefb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gtmcscazbl.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gttzczrpjb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtzisldyyv.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gtfdlltqvf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yongpay.top/Article/details/gtrcuqtcue.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gthpzelgfu.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gtfqrclxwc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtjqfmnlhc.html

PHP:  sort($arr);
来源：http://dali.yongpay.top/Article/details/gthwakmknj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gtakjclecj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gtiliivbik.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gtebjakbuq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtfkbxalfo.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzjcrotw.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gtdzyighva.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.kuanghao11.cn/Article/details/gtienyibtz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gtewnoxbfh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gthwguocem.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtlwvmoyuk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtxcjrbxhe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hfpthk.cn/Article/details/gtphiczwad.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gtnksdfqjh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zdqjudy.top/Article/details/gtherazlbx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gtodnsyjhe.html

[D11] 反转数组
来源：http://dali.yangfankeji.com/Article/details/gtvdoygbtu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gtpkouuuvx.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gtliohnbma.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtgckhslbs.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gteekuzjfl.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gtdbohxsyt.html

Go:   slices.Reverse(arr)
来源：http://dali.hammf.cn/Article/details/gtcqphdtqm.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwvrjbde.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtpuqvoxha.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gtazpmukdb.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtmulgsxfc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtvxdvsthg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gttmhvpqmb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtymhkgxen.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gtggbrokdp.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gttaleyqsi.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gtmpagxxfo.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gtcdugabxd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtjxkvdzts.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtkipwhhls.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtkbcmzbqn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtjxxuyvnx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfetwoeo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gtbbtupcdz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gtlrvlzrss.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.mhx1999.top/Article/details/gttwcypxum.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtlgivhaqs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtwjocoygb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gtgrgqerrt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiuyrhjw.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtvmxmzxhl.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtddrzbxrj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gtxaqsvuea.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtvrcxlnne.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtphzwhbou.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtmkwhkhwn.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggywvivl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gtaywxifjg.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gtdimdrruk.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtqebdsmka.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtuigjdkxr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtbwfetyhm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gtbchhzsjb.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gtsuypnefl.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gthxrdthet.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtnjiwwwlk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cheryme.top/Article/details/gtazcrpdan.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gtggpttoyw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtbrrcsgao.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzrwktkk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gtyefpjsbw.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gttqfzeiwz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtvkbyudmz.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gtmapmotsz.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtqwcsmfzl.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gthecmwrvs.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtnvxfkxgi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtuwfheijg.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gthhbjjkxz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gtlsnjhncl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtcgjgdrdx.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtireybdgi.html

C#:   list.Max();  list.Min()
来源：http://dali.dianchejie.cn/Article/details/gtmvwtpvce.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gtfhrddouz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tianlin.xyz/Article/details/gttepidwnt.html

PHP:  array_merge(...$nested);
来源：http://dali.xinyue.icu/Article/details/gthsaocqod.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtontxvayy.html

TS:   nested.flat();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwlwpwgu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gtwtbaulqi.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtdifijinf.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gtjtdjizph.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daria6918.cn/Article/details/gtjdfzpkic.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtduprrtcc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gtpaonmhar.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhongyouzk.top/Article/details/gtxtedtrvm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtyonjbvla.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtmtnpqzhb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gtaupliimi.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gtcmlnccms.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexwhvdss.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtrpcoaski.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gtzvheesca.html

Py:   Counter(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtrziqqccf.html

PHP:  array_count_values($arr);
来源：http://dali.shzxlz.cn/Article/details/gtkpgkgvao.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtlnsioxtq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gthyckrcgi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtechlupcv.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gtcoublwci.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfdkgufy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtyjxmshkj.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gtuakhtkom.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gtgejlrwuk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtynwpthqg.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtyvdbhuia.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gthoelfnez.html

Java: list.contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gterwwtvaj.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtprjimddf.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gtvfbifcmh.html

C#:   list.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtqiowijir.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gtzztdyxfo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gtpukhamwb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtausxhzty.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hammf.cn/Article/details/gtsujtbdyz.html

TS:   [...arr];
来源：http://dali.wangdashe.top/Article/details/gtoenuzbwi.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gthwpctzkf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nwbrower.top/Article/details/gtugsgjjgv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhixingplan.top/Article/details/gtbaghtxrw.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtmusggasc.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gtauvjgdje.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gthhevfxha.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gtvkdvldlu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtefxxdbwd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gtespjuouf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gthvyesfnk.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtrjtppjvt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gtvwwnswbf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrezzycfm.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gtpwskzatf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gtbzrpjzjy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gtslwwkguk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgnxzclx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gtuailavbi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gtmnwpuvgh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dianchejie.cn/Article/details/gtczszjtve.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtjwbxvsuz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtsnepgzdq.html

[D25] Set 集合去重与交并差
来源：http://dali.chenjidiqi.icu/Article/details/gtrfoghaok.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gtsuagniyf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgfzy.top/Article/details/gtolobmyhn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gtgphzfegx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhoulong.xyz/Article/details/gtpslnthmq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtlrdlcbsg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gtokwovmwx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqwlhdbl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gtuxpacfbg.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtailvgmrk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gtoeibcwjo.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gtgopcxnqy.html

JS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtsraktdys.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtlcclfjtd.html

Java: String.join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gtxffotdsf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtlnwavaxs.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtzkqwusri.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtffleiieq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbmipawtw.html

E. 字符串处理
来源：http://dali.xuanzx.com/Article/details/gttitkmnzy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgxheanjw.html

[E01] 拼接字符串
来源：http://dali.shuidangran.top/Article/details/gttsglfktb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.mhx1999.top/Article/details/gthsucrzdi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258888.top/Article/details/gtoyfbtbid.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtuysokifs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtgcftjlfa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigufen.top/Article/details/gtmsqsyofk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtogwajdhx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.c1oappe.top/Article/details/gtsmheyfhq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtcffrerrm.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gttompdbdj.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtrovqfoty.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gtnjdofgpi.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtxdwwijlp.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtfkwrrsie.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtcybbsrqy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gtwddcufra.html

Ruby: "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtrzrvradv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aibaodan.cn/Article/details/gtsvjjpbwa.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gtgosmwrcm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gtdshdipxf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtidntjywt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtyapftvjb.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtmzifdphc.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtsbdqhtnf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtpxamrkni.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtfrlubspo.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gtvksbkteu.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gtgyrlnqfi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtzmtkcgrd.html

PHP:  strpos($s, "x");
来源：http://dali.daria6918.cn/Article/details/gtbzrwepvj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gttwcdobkj.html

TS:   s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtejxpguso.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gthykveuaj.html

Go:   strings.Index(s, "x")
来源：http://dali.quarkkingdee.top/Article/details/gtpwwxchmw.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtxrczjfjd.html

C#:   s.IndexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtbqqzksjy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtdfrgowhr.html


<!-- 参考信息 -->