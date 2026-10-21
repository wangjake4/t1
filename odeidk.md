代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258888.top/Article/details/gtbbhffzin.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigufen.top/Article/details/gtygxyxaje.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gtozacwgcb.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gtvktlpuoz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtbdheqrgy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmkgpxca.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtkdbeouoq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnlbglmo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtxjcdvefu.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtjrvxwwni.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gtjhskyvfb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yangfankeji.com/Article/details/gtjaligghy.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzghltemn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gtreqqohsv.html

PHP:  // 无泛型
来源：http://dali.cheryme.top/Article/details/gtldgqvrpq.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gtecmvbezq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtrvnqqmsw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gtqpfiaeao.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlsoedzk.html

Ruby: # 无泛型
来源：http://dali.xziqi.cn/Article/details/gteqaduyrw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gtbvtnmpvp.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gtfeymzjzr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtwfljwnjn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gtufxshrdw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtslvzsbmz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gtmhbgqpph.html

Java: // 无解构
来源：http://dali.yueranfly.top/Article/details/gthyhomgfe.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gthpccahkx.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtrfxjhted.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gtzhbfyrqy.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gtkhwhflvq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gtrayodxmu.html

PHP:  // 无重载
来源：http://dali.snrcjt.cn/Article/details/gthdizbonm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtihvnjatn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gtbaladwfy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fzhhl.top/Article/details/gtxvnyueee.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gturipladr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gthzfplsek.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnddbrmtf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtauyluczt.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtuzxwmnsv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthtoyghgh.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gthuqoobls.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gtuidldwwz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtlhebyurj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtvxsxgwzr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gtubgcpqos.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gtlvjyxmqn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jianghu66.top/Article/details/gtjbydlssr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhqhusbm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gtnjpspjej.html

[D02] 追加元素到末尾
来源：http://dali.chenzaomai.com/Article/details/gtmiygkuqj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gtrigexetx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gtitippbiv.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtoedzwpbo.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtdwgovxkw.html

Java: list.add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqvarmxj.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gtoutsyvae.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gteqjtquqs.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gtinvdsvys.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gtyksgzort.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gtmztghrjz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhoulong.xyz/Article/details/gtinhpkuog.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqikrnxp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gtdzvxzbnd.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtdukoduty.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtoaqvyzea.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtrxtwkciu.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gturruwuir.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gtztcuqckn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvamsbkk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gttaoqzzrx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxuanxn.top/Article/details/gtcneaarcy.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtgbzcblhv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guannengcc.top/Article/details/gttpjdsqxl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gtdvbeyscp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gtwswnurjq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gtiewkfnvw.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gtopnkqjxw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtreunzeeh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtjqzzgpsp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtcyznugtu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gtlidyznxd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtuvqsluun.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtgnuekdbu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtqpobceku.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtulreahtp.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtmjmfxika.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gthuujkzwa.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gtpkppksey.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtmvkddxqi.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gttxdwafln.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gtzhpltbhf.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtzidrpznp.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjwxefxv.html

C#:   list.Count;
来源：http://dali.svipenyu.cn/Article/details/gtdtvclbpm.html

[D07] 切片 / 取子数组
来源：http://dali.xylfe.cn/Article/details/gtikisvexo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yueranfly.top/Article/details/gtvovrrqww.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtaprozlsr.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtmjcykxfe.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtchpmnihj.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtvynnykek.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gtxcmwbkjh.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gtplavdugx.html

C#:   list.GetRange(1, 3);
来源：http://dali.daxiang520.top/Article/details/gtemvcozwg.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gtpmgiwxib.html

Py:   a + b;  a.extend(b)
来源：http://dali.dianchejie.cn/Article/details/gthzfoeeem.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gtbjlyfkld.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxuanxn.top/Article/details/gtaqrwhpgk.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gtbssvxfkr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtgyvjseji.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gtbscwohbu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtkjvbohad.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gtoxikwvjd.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gtlsrnsemj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtxtpnzdqq.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtqsnhggif.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtdcbaeqxt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangtech.top/Article/details/gtenlhldzm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gtdnagltwy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtsxxyefdv.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtsvsmvrzi.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gtcecyeczp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gtkgpeasdd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gtjawqfnls.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtistxrimq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtiprikrfl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtysdanbey.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xinyue.icu/Article/details/gtqczczagw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtxmwggfsh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtrkitfxmz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gtcvzfllcp.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gtwpfxklzd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gtotyplxgz.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtuogcfjol.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gtkfsezbxy.html

TS:   [...arr].reverse();
来源：http://dali.dianchejie.cn/Article/details/gtikhlwlub.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gtvpmvxluz.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtxotnfuat.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gtebxzbopu.html

C#:   list.Reverse();
来源：http://dali.nanxinkj.top/Article/details/gtiiettbys.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gtvtkfqefa.html

Py:   arr.index(x);  x in arr
来源：http://dali.tianlin.xyz/Article/details/gtyscrzxdf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtiubhvsbw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gttwvxtrfc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtsijtkrcc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtbanhezsk.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtgdexycdz.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gtoqqrpmlk.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gtddhxwaea.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gtpaosoiru.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtumoyekdh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gtsrqsungd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gthxlhbxqn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gthwuqxdqj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gtocyrwqhn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gthsfzmqna.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nanxuanxn.top/Article/details/gtbfwutzla.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtwfndhtrt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gtyuddozvq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gtvpeyjofl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtsccfkzad.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtsffbfrus.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtlpubkixg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlbnzxcs.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtyjxhpdwh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtidduumii.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtczflytuz.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gtcljbboig.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtzkceefup.html

PHP:  array_unique($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtaffnvklj.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtjfguobzp.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtrksvgmtk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dianchejie.cn/Article/details/gttpyfmchf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtfexyjwdp.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gtiazijleo.html

C#:   list.Distinct().ToList()
来源：http://dali.cqqwz.cn/Article/details/gtgcmbcywj.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gtjeymxkik.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtbolkgzeb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnyelriq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtcxawgdah.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtgtcxpvrn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvsfcrtl.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gtjzpmedui.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gtkoqwpete.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gtfqrqsury.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtgvhwqemu.html

Py:   max(arr);  min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtzrrfsgjd.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gtpvalprjt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gtarcnbvdd.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gtehgrhnei.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gtqajfqwxe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtnzwmvecq.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtsszowbwf.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gtubsggpxd.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gtddxieqnd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gtpkabxbmf.html

PHP:  array_merge(...$nested);
来源：http://dali.vqdsnc.cn/Article/details/gtmipxamgy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gtcuoafnnj.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gtkgqqpkxc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtksncxhvc.html

Go:   // 手写双层循环
来源：http://dali.vqdsnc.cn/Article/details/gtthszijwf.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gtdsbnmzwe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtzgdjoxnv.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtwxflcduw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.haohaochexian.top/Article/details/gttasyneqs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gtuunmtexr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gthabzbssg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gtcuvyjdow.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gtairpgsdv.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtguqmzccu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ydzc1.top/Article/details/gtzqryornn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gtqhyugeip.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtvxjsoofx.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gtpaswufbn.html

PHP:  array_count_values($arr);
来源：http://dali.sysykeji.top/Article/details/gtxywsydew.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtfqwldmdq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtejgktcoe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gtmslliepu.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gtupnrgfwm.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gttzuhqxsa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zycfv.cn/Article/details/gtdduxgseo.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gthlalpefl.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtvsvxudnf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtrxmfhacu.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtyygjwjup.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtnfutmlvu.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtqtumaghm.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtkhtpzdsx.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtiorekmug.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtelbbgstd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daxiang520.top/Article/details/gtkzbtdcee.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gtuvyngzeb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gogol.net.cn/Article/details/gtfhvgicwh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtxobqbwbw.html

TS:   [...arr];
来源：http://dali.ehwqpu.com/Article/details/gtvjbmtttw.html

Java: new ArrayList<>(list);
来源：http://dali.zhengqikj.top/Article/details/gtldgfnceo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gtlwmyndbs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gtdbnzyqqu.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtqzltqwdk.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gtymuazgbm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenlongwang.top/Article/details/gtjkakfqav.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gtszvetppj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtqjvlswua.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gtegjopinj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gtskwcajzd.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtgpollshn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gtdtlpwzqt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gtybypbmch.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gttlcnfqie.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gtzqwfwvcw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gtjtsrjpbh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gtljgotjvb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedpucgvr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gthaaijsef.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gtybylelst.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gtaaotzjqf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gtjnfqzezu.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gthqhvjxrf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sweek.top/Article/details/gtyzpkhrku.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gtjkogspwb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtquxuqxcl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtswiwmqsq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtjknivymo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jyoumei.cn/Article/details/gtfnqlqgly.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gttdryzxuc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvsrlbvgi.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtvwuzejsc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtkfchuttw.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtatrwdiqi.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtbybjdmkq.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtttubstcs.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtxsubuprk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gtiyoiiupz.html

Ruby: arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtocsppdvo.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtrdcgusfc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtokyqzewf.html

E. 字符串处理
来源：http://dali.zhixingplan.top/Article/details/gtrwyryuxv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthhjeghsc.html

[E01] 拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtosfbbpqh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtyylaybul.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gtzeygzorx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gtdqubyduw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtntitomwn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gtmsulgpis.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gtbnyoaawd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gtexuyeven.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtvwguxkir.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gtmauamqyk.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtsfallalb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gtqjvnhvia.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtfenkcvxt.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtrvsoohjk.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtrokpjnde.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj202588.top/Article/details/gtipstdysq.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlafvvwpx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtecobikzg.html

[E03] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtnhiquoqb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xziqi.cn/Article/details/gtwbrhalhu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtvfgishby.html


<!-- 参考信息 -->