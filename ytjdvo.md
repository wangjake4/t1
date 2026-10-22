代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gt2aviidwlv.html

Ruby: -> { puts "run" }.call
来源：http://dali.guannengcc.top/Article/details/gt2ywvrcyax.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2hmazbrys.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gt2wltsiytk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2lhccowqr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gt2yoalnicp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gt2mlprcapu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2pttwkhnk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2qprjbhwj.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gt2dyljzlsj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gt2limvyrie.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gt2hxutqcbe.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gt2scolvcxb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gt2rqiqdkqm.html

PHP:  // 无泛型
来源：http://dali.cashguo.top/Article/details/gt2rwygdhvz.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2ffqsyymx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gt2hodmocxn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jiagoushi.top/Article/details/gt2orjutzis.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gt2txydzuof.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2ayxebywp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gt2iqhqwlob.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gt2picwqjow.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gt2osowkrea.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndrdrxqt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gt2tadtgequ.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gt2afqzmpbc.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2tsarqpmo.html

Go:   // 无解构
来源：http://dali.ydzc1.top/Article/details/gt2nurbqqii.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gt2dbmxcnhu.html

C#:   var (a, b) = pair;
来源：http://dali.vqdsnc.cn/Article/details/gt2vwsuhrtu.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gt2swuamyqz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gt2buxukasg.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gt2xqotfmfc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gt2gozqxbhr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gt2isdayrjh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gt2nuvivwat.html

Go:   // 无重载：用不同函数名
来源：http://dali.pycfn.com/Article/details/gt2foeijxfa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gt2xpoznhsi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gt2vuuugrsg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2pnrbruwd.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdheilyc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jrsppeoh.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gt2jfgzfyva.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gt2yzmkjeqy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gt2zzarjfjt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2kkhsbmid.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gt2ppspukzn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gt2shzpobse.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gt2qtufpkfb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gt2fceldogn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmveozcm.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gt2tuefakaq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gt2qqgzlmsn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuanzx.com/Article/details/gt2ymhdyfzo.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gt2bofdfumq.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gt2uljykhuo.html

Java: list.add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgxncnjh.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gt2qtgjfemy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigufen.top/Article/details/gt2tyjraqxz.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2erlklcps.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gt2esqmgzin.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2fmkchuaj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.andypj.xyz/Article/details/gt2jlqfffqq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gt2myfgajfz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gt2qcmwnlwf.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2fpywjgof.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2vxogstmu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbeayjol.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2sxetrkky.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gt2tkoobjzv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gt2qesnzifo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gt2mrazhfns.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.kuanghao11.cn/Article/details/gt2ogwuqtab.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gt2ymrbpiux.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnqzz.top/Article/details/gt2vyeouher.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gt2bilnxxav.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.smart0.xyz/Article/details/gt2rrdfotlk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gt2lhbfrxwt.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gt2dayoqmeb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2iwfvgbhq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gt2aiwqxciq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gt2alggsjct.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gt2zwnpudyi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gt2qwywonlc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2fceuklwl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2yxensacp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2bbwpxthd.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gt2xsewoyvc.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2diukbxmw.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2qdsgzgfx.html

JS:   arr.length
来源：http://dali.tanke756.top/Article/details/gt2qzmcehdr.html

TS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gt2gbwcxytk.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gt2amhejftd.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2ohowfxxf.html

Ruby: arr.length; arr.size
来源：http://dali.gogol.net.cn/Article/details/gt2gsrioebr.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gt2xhoqxhrv.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkllrplx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gt2jgziaheb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2vnkadppb.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2hjidtcji.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwylgffd.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2zoztmrnv.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gt2xjxbzepe.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gt2qvzeteia.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gt2wljdhbbi.html

[D08] 合并两个数组
来源：http://dali.fzhhl.top/Article/details/gt2pqrarwra.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gt2nuisxwas.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gt2mztwmjds.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gt2xzmhgaku.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilciwdom.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbyyxhyr.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gt2slflpias.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gt2tcroosrs.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2cgdbfyee.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gt2uhxszgoq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgelnbhg.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2ipikxzdg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gt2knkbivmj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gt2zxytvnhq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gt2lstsrtoc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2bhxxjris.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrajphmz.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uypobzcd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gt2iihitygx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2vljgbtsj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gt2lnvadcyo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gt2sseuoauz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gt2gmdwdqnm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gt2bclwavsb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yangfankeji.com/Article/details/gt2ibqyaycl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cdnleiting.top/Article/details/gt2mtfrppke.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gt2bfnpwafc.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gt2cftakqsi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.quarkkingdee.top/Article/details/gt2qncrminu.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2fdwcukiw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gt2okxsjkmx.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gt2rblealtu.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gt2rhwgsbfb.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ubhoaxfo.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gt2gkwtghxl.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2xievxhru.html

[D12] 查找元素下标
来源：http://dali.yvedp.cn/Article/details/gt2tjcpajzo.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gt2wvhkbrnt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2kypdtfru.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqzyeyus.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gt2xnxlwsay.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gt2auhjnhsy.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2soqvarbn.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gt2ytiuauek.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gt2krmwdluh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigfzy.top/Article/details/gt2xcnlaoxg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.9152youxi.cn/Article/details/gt2rmewvkfo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gt2cnfrxbqh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2fwabvssq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2pwjcgqiv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2jqnqorhh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2xcupfdow.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unnxmwgx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2mfakrieb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gt2tijvbehm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2ubzgwnfn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2eghsqzqb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gt2iidvyxcv.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2jesmptya.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gt2gttjgofq.html

Go:   // 手写循环
来源：http://dali.gaohongyu789.top/Article/details/gt2jjsduuza.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2dbrpilmp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2jrsqzpdu.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gt2qwrbavez.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gt2cfbxsygg.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gt2ziiqlxxw.html

JS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gt2nhmwcxaz.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2xiwwqtmr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxwgpfxl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gt2zignybzh.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gt2xlmpmkwx.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2drybxmbm.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gt2tmsasels.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqkgpzlh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btqdngpv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gt2nwxlgzxj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2ydgyiqxz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gt2alkouaez.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gt2cjhwqkfs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jobyvpok.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clpxrhbn.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gt2ghrcxazc.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxspopph.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2flodizmg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpnhqpux.html

TS:   Math.max(...arr);
来源：http://dali.dianchejie.cn/Article/details/gt2hvpjeomc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gt2tekqfuga.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2ogwtpfln.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gt2ckfworqu.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gt2udevfwod.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gt2ksyhacne.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gt2lgrfwrvx.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gt2jepgzyoi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxxvcydk.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gt2fkohjqcp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gt2rjtyxrih.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gt2edincvya.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gt2zwitcese.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjwozctd.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwnfnare.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnftvthh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gt2xqcwbdcn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zdqjudy.top/Article/details/gt2pjtuhnbp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gt2yzqihqep.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sysykeji.top/Article/details/gt2oxoyvtjr.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gt2eskvwgic.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gt2jpijppzb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gt2byqfzijr.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2gtawzfrt.html

Py:   Counter(arr)
来源：http://dali.yj20258.top/Article/details/gt2lsduroxw.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2wtmxxpgz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gt2mlkqxjar.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xinyue.icu/Article/details/gt2oiwccjpm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gt2ormvlkxw.html

Go:   // 手写 map[T]int
来源：http://dali.gaohongyu789.top/Article/details/gt2jjmvdfsq.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gt2zobeiakr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gt2rupqqzrv.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gt2jmikzamw.html

Py:   x in arr
来源：http://dali.birdmap.top/Article/details/gt2tcnhnmuk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gt2xemtzvqc.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2btphieip.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2reukeftk.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2tbesumus.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2dwaayprt.html

Ruby: arr.include?(x)
来源：http://dali.guowangkeji.top/Article/details/gt2wuaajeqj.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gt2esjnnwle.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gt2icpviyyc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2zzshtdcm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gt2lgxzgtkd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2lakxtklq.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gt2giqeufvu.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwidkzqy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gt2vwfjwwqk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gt2hhxyaayj.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2azckvtsq.html

[D23] reduce 累积计算
来源：http://dali.andypj.xyz/Article/details/gt2tddoloet.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2tcswyfkp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2qqbtdhrz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2cpoxyjwj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2vlvrofjw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gaohongyu789.top/Article/details/gt2oayvtsdh.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gt2ensmlwky.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gt2whnfotmi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gt2biuapfzp.html

[D24] 字典 / Map 基本操作
来源：http://dali.svipenyu.cn/Article/details/gt2sfooxvrg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gt2cwqautsj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gt2gxszhftd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gt2zeysffsz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2jjyvgfbv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gt2womhqltv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gt2ipjtdfkv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vuigihju.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gt2jwecgkvm.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gt2vjqupvva.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gt2txyhtkdw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gt2yqlwyxqp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gt2kdupscmg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnmuaqua.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2rvlokkci.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gt2cwrdtahm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hfpthk.cn/Article/details/gt2pdysyrad.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gt2qajbegli.html

[D26] 数组转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2mnlfozhi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2gajppvkj.html

PHP:  implode(", ", $arr);
来源：http://dali.bjfxy.top/Article/details/gt2atapfygk.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2qkjtcosx.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2gafzxabo.html

Java: String.join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gt2xfvvxipv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwzqrujn.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gt2tbjmnkzq.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gt2uimxqsnu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2onoxkxlb.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gt2pumheggi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2pssmihgk.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2gdjjkhut.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gt2uyzqazdv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gt2xouilyan.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gt2qergyudg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pvaxpcky.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gt2qyofmdky.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.havefunace.top/Article/details/gt2jnuiexxe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gt2mwgnlkeh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2iythldnh.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gt2lntuyrcd.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2usxhcehp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gt2hvaakdfq.html

JS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2jgbfqpiq.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gt2zyjtqwil.html

Java: "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2amazulyg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gt2zbuerazb.html

Ruby: "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gt2kgzhpupp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2mnbntzlt.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gt2rnsyclde.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxbwydrb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2fetezudm.html


<!-- 参考信息 -->