代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.shuidangran.top/Article/details/gtpgdmxonv.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gtuooxgeai.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gtlwtchawr.html

[C13] 类型声明 / 类型注解
来源：http://dali.jyoumei.cn/Article/details/gtuupmlxqg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gtgdfjhssl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtodslwkyk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daxiang520.top/Article/details/gtslziybhn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtboxludqc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtnojrqnsd.html

Go:   func add(a, b int) int
来源：http://dali.yj20258.top/Article/details/gtrwfbagcq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gtcvrrprak.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gtevkzammn.html

[C14] 泛型函数
来源：http://dali.hysaishi.cn/Article/details/gtfkgalgci.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gtznnvfxsk.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtmnjqanpi.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtbwlbrgip.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtntmgxnye.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fengsongda.top/Article/details/gtluuvrjue.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gtypxxkpwe.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtpfjbdnit.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gtadopzaac.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gtjhzbtewc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gtiojovcmq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gtsxslwnuh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtnmnphhys.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gtypybnvrg.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gtvsvpsidg.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtpqpnuaoj.html

Ruby: a, b = pair
来源：http://dali.aibaodan.cn/Article/details/gtbrqvakve.html

C#:   var (a, b) = pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtireomfyd.html

[C16] 函数 / 方法重载
来源：http://dali.ybcxt.top/Article/details/gtfjnjapoi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtzhbruagz.html

PHP:  // 无重载
来源：http://dali.xziqi.cn/Article/details/gtszjyifln.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gtxldvretc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiykbsbw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gtytenxnqe.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gtgmuoesfb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yangfankeji.com/Article/details/gtrgmhlmbn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cdnleiting.top/Article/details/gticyupvft.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtbljjvczz.html

D. 数组 / 列表 / 集合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodyrdvtr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttrvxccxv.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gtynyeoybe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gtyqufociv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtffsjufrx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtkhnkwgto.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtixgcafcp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnalffglh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtcimbbmsx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gtoohqxuxz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tanke756.top/Article/details/gttpzwvhwi.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gteelgndgx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gthzdojjtw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gtqdaqxgxv.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtledfkcjk.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtuhakrcga.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtyllwmlmr.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gtcamuqgpz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gtidrvhusl.html

C#:   list.Add(4);
来源：http://dali.sufxvd.cn/Article/details/gtdiajedlp.html

[D03] 在指定位置插入元素
来源：http://dali.cqqwz.cn/Article/details/gtzhmgmzhz.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtnedpawlh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gtjsaaqnqs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gtlahtjish.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gtvuuukism.html

Java: list.add(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtixxkqklk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj202588.top/Article/details/gtxdgjfslf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gtbtklnabo.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtsbbrzump.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtjijgdcma.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xylfe.cn/Article/details/gtniiunizi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dianchejie.cn/Article/details/gtbjwssxsg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gthiwzppfn.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gtydecaufd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtcicgjjez.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gtnootdcsr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gtmttioovz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gthlnipcnf.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtebdixuot.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtpveokdow.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtksojqbdt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtmysxjqzq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gtnqqtvkxj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmmewnow.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtlyoggzlm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtnxirvmvr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtxnizbxsz.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gtydaejfln.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtjqjxedcv.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtioapaebi.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gttjmcsnpz.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtklrxocab.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtzgjuodvz.html

Go:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtojhixgpy.html

Ruby: arr.length; arr.size
来源：http://dali.havefunace.top/Article/details/gtkyqwlitr.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gtuzqwzhoi.html

[D07] 切片 / 取子数组
来源：http://dali.gzhubu.top/Article/details/gtqrrjfrzh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.feifeiyinyue.top/Article/details/gtoomlqoid.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtxoispjna.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtguqcfnph.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtfvrdgnik.html

Java: list.subList(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtripcbnon.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gtidmfohjy.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gtxxihwmbj.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtdfqvtbby.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gtenrucxjf.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gtiwvarvvy.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gtiwearpyr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gtrwejetcd.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gtljetsuex.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtfwpsasvr.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gtofhyaepy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtumdpwwrm.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtpvfxoben.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaetygcqe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtcpdchtcx.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gtdcudaych.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gtvlwqdkev.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gtmdfbdtrd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtcodwuqtw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtatafdpaa.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtkfmepvaj.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gtpvtsnfhe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gtagqrlxxz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gtffhwphfq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtcfntcxok.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtievqzwli.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtzjnijhej.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gtzjiymlev.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.snrcjt.cn/Article/details/gtrafifxlm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gtwrryyakq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gaohongyu789.top/Article/details/gtizrtyfsc.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gtwhdnjvkw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gttfnftgvr.html

PHP:  array_reverse($arr);
来源：http://dali.zhixingplan.top/Article/details/gtolnpcnpl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gticneyevu.html

TS:   [...arr].reverse();
来源：http://dali.cheryme.top/Article/details/gtodalieqc.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gtlrcloqhs.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtqugwodec.html

Ruby: arr.reverse
来源：http://dali.yj20258888.top/Article/details/gtedekrjbr.html

C#:   list.Reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtzibnyhng.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gtugmskmoi.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtatcwxagg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gtmlesiaun.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtiqlpzbub.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtzzupprwa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gtgwnsfnjn.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gttrfqazvd.html

Ruby: arr.index(x)
来源：http://dali.cdnleiting.top/Article/details/gtjnxhlyzh.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gtiozbcliz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gtezqxtujy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gtsarfyqeb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebdcmttq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtifmdqjcy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtoysdsghs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuanzhike.top/Article/details/gtcmyxfing.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmtqngvd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gtvfdekafb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gtszvrspoj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtghgegbfl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gtseidnipq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gtreqyxizy.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtxffhwsye.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzzutvqr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtwloolngu.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtpfdywulo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtcpiktljy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtqikmmywz.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtzlqmuutj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtlwltissk.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gtrlbkbspr.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtfqcworjo.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtiphouavl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtfbhqvqfu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gtiqnbxxow.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpestprtk.html

C#:   list.Distinct().ToList()
来源：http://dali.hnqzz.top/Article/details/gtdttcefmb.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gtnajrxzky.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gtwyymqtrs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gttbssieah.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtuyhqkgpc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtogutwlrq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gtoehlgjms.html

Go:   // 手写循环累加
来源：http://dali.yuanzhike.top/Article/details/gtmfmpdfmc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gtibrdpbnw.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gtgnjitpyb.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gtxcdrpvue.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtoisphkii.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gtzkmxgbov.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fengsongda.top/Article/details/gtjzxzhhrw.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gtewtwqhct.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtqpiklxxd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gtwihylpjf.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gtzeewmlvy.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gtghycvvca.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gtwnejdhtq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gtbrttzwgf.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gtmbkaylxd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtotthrkum.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtjbvuugkp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenzaomai.com/Article/details/gtujlvueps.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gtyrspggen.html

Ruby: nested.flatten
来源：http://dali.jinqigufen.top/Article/details/gtpunettvo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtzkfjjuaf.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtgnaoaqdk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gttcwcymen.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gtsuqeapuq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhengqikj.top/Article/details/gtauagpdci.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gtqhtkwyfd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gtzynrdsdr.html

Go:   // 手写 map[string][]T
来源：http://dali.xuetiantiany.cn/Article/details/gttauvfgij.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtqqauphue.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtemgvurrm.html

[D20] 统计每个元素出现次数
来源：http://dali.daxiang520.top/Article/details/gtzsufwoac.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtjkpwssog.html

PHP:  array_count_values($arr);
来源：http://dali.gzhubu.top/Article/details/gtikaoxppk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtmgtsytcy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtaqwogaig.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gtwaxidvgk.html

Go:   // 手写 map[T]int
来源：http://dali.ppjwa.cn/Article/details/gtgdujenfo.html

Ruby: arr.tally
来源：http://dali.cashguo.top/Article/details/gtnmcbwyse.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gtdeqfjpvr.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gtuwzueufz.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gtptlnsfhe.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtgahlbmjh.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtsrnsddvm.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmplougqb.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gtirnpbrvw.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtzhhrtnvv.html

Ruby: arr.include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtusqzvtzx.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtikicclvb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yanxiufei.cn/Article/details/gtbdldsopi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gtxslgrtlc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtspcddyjs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtubcdzbfp.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gtlrethehw.html

Java: new ArrayList<>(list);
来源：http://dali.ivvv.top/Article/details/gtjhjyoyei.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ybcxt.top/Article/details/gtvzunnddq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gtkttxpqwc.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gtdngmvouv.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gtchnrctjj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtlgjszeao.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtmodtlcjz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtondrmtly.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtclzfcbgq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtlvfekgyb.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtwjocmsqj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhiwuduotai.top/Article/details/gtbwdmsmze.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gtipgubtix.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gtucbcofcx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdlfnyls.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtvplgiowk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gthkiecjje.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtfyyeorsg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtwsyffqak.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hfpthk.cn/Article/details/gtbexdjyda.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gtblrgqksl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shzxlz.cn/Article/details/gtebpgcufo.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gtkvfirvkk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gtmjdrcdlk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gtxqhhwfci.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gtsqnhzmaq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gtderfqxif.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gtfhchhcuy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gtqlbmnfhv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmjetzuw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gtsidvcpli.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gthyuuprlv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtalmkdotp.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtevkqbzqh.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtvtmctxdn.html

TS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtkkyonmxs.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtlvtkogga.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstmsvmos.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtlwzdkuhl.html

C#:   string.Join(", ", list)
来源：http://dali.sweek.top/Article/details/gthcjhxhsh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmicpswob.html

E. 字符串处理
来源：http://dali.9152youxi.cn/Article/details/gtujbahpfb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfwkposlt.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtgaqhyozr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gteohigvwj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gtcjtbxxok.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtqhskqphu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtdkymkfur.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gtqrwfuyuh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gtxrirxynu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gtpwjfyhec.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gtudgbcszw.html

[E02] 重复字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpmpftnz.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtrmsyrjvy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gtripsyylf.html

JS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtcwytnguc.html

TS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtjvzwmvmq.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtsfrepnxz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gtaqqqkivf.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gtrcxapkxf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmgivbjt.html

[E03] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtmkzkrzhf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gtogeuqkgu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtysaxusgx.html


<!-- 参考信息 -->