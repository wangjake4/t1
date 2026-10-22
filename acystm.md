代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gtxforyzcq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtghnrfrzt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj202588.top/Article/details/gteasempiy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtddfkvlde.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtolheblfb.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gtchzciyts.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gtgaipkbwm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gtbnycymvx.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gtolgryzmi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cdnleiting.top/Article/details/gtsvxlqoao.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtdcdqefke.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtfowzmbsy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gtjzwiiieu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gtgoywckjt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtxxqhomjp.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtdmkudpcl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuetiantiany.cn/Article/details/gtqyfcphhu.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gtoniognrf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gtchsfmusg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gtbqwabokc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtweptgumq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gtuxaqysbu.html

Java: // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtirupdffl.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gtifyftcar.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gtvdmscsbe.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gtprxebqps.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gtwrevzpok.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtpmjivjyt.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtddblncma.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtynafbqvm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gttbzxbxam.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsskxmdeh.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gtiewbrodf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.haohaochexian.top/Article/details/gtktpvpomt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxuanxn.top/Article/details/gttlovetrw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmprlgrac.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gtmtwbeakg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmixvwol.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtexpthtrz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gtkbgeeiau.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gtzlpbzplk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtyrplfkbo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gtpwksrejj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtxvgmxjkt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.redwolf501.top/Article/details/gtnyfenaon.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gtqtgbxhhw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gtsursiazf.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gtklroxebu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shzxlz.cn/Article/details/gtnrcvmmfr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtdzbiunzb.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtakagpswr.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtkkpuumhz.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gtdtukdcst.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gtduiqhyem.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gtgvzqfgna.html

C#:   list.Add(4);
来源：http://dali.dashuyun.cn/Article/details/gtlyargisq.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gtehppftts.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtqabarlfi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gtiougxsnc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gtaxisvgcc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtqbjmysdl.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtbohwelab.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtpmbpowcd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.0kj1m.cn/Article/details/gtmefneihc.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtqcbaxchv.html

[D04] 删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtxcitzrnk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daria6918.cn/Article/details/gtipdiemcy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gttbyyawug.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtukdkyecr.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbiewmav.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gtaqesddbm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.havefunace.top/Article/details/gttjdvutkt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gtfcnlewjp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtefbvkj.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtceannpyh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtqrgepzrl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtbnrmfenv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtygwxyyqn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gtmsvtfsrk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtziygnild.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtxdwrgjpj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtnytrrrkq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtxseupthb.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtevnqgwht.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gttirehjpj.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gtsfbeycbo.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtiygnegtm.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmaehcsxv.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gticuexqme.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gthkdyrvbl.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtdlgdktcw.html

C#:   list.Count;
来源：http://dali.svipenyu.cn/Article/details/gtfgbqputp.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtwsktjcnq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gtuljcejtf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwojwdstt.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtuqgiflee.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntugyhrh.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtxdgtvyro.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gtcysvjenf.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtmgjlguuf.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gtyeeumvxn.html

[D08] 合并两个数组
来源：http://dali.nanxinkj.top/Article/details/gtgnchfdia.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gtqsmgzpwn.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gtlukvmsyi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cdnleiting.top/Article/details/gtvbpcmrxi.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gtpamixzgj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gtgqurqsbk.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gtxhdiczby.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtvrekykiu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcexthfhn.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gtjamdlxdw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtezqlfkew.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteskspqwp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.c1oappe.top/Article/details/gtrraycyay.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sxryk.cn/Article/details/gtzntptdxu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgnaoybk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtuuxysgfs.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtwwoxihql.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gtcnveflhn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.quarkkingdee.top/Article/details/gtyclwciao.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gtgrcemthh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtphabtfsw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtjwsfcvxv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtiejmexob.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gtwbhkibhs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtqnmsyouy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenjidiqi.icu/Article/details/gtamxucqvl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gtxvptkyna.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtsaacdhwh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gtbyzaarfw.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gtgyexaoes.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gtveidyhwa.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gtbnfrjqrk.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gthtpknyoa.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gtimrqcdhq.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtjiocijbt.html

C#:   list.Reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzfwxucs.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gtbamtetik.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gtlhblrbrz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtekwgbjlf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtogbnnzkt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtvvlehnzv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtxlboumgp.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqqnclpu.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gturfberbx.html

C#:   list.IndexOf(x);
来源：http://dali.c1oappe.top/Article/details/gtuzsysjdx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtqnvgjeyl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtxetfkkyj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtbeclromu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtxconelky.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpageengq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ybcxt.top/Article/details/gtwqwutmii.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yanxiufei.cn/Article/details/gtrdobtpwm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtaizdxrvp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtmwuqrnim.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gtxfnnniks.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gtwwvdgwah.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtxnqnwexl.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtjabmdnmt.html

TS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gtmsgosudb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtywsqjkxo.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtkvgdkoyn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtdrvemhgz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtqonyzhns.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gtpjxaqfms.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtqycvjmfh.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gtxbuvdvzt.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtmuvyhnyd.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtdicknwmt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gtvnrtswok.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gtxxucmfmz.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtbzqstykv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtfhrcsnjd.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gtwbuuleuq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtydxjpwzg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gtmqknlbsu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtchhqiklr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtcbfbeurm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gtaokluwxj.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtzwntmkew.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gttdwlwgza.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gtznyrolvi.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gtlrbdmupy.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtnsnrrfzf.html

PHP:  max($arr);  min($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtdbjdhycl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.9152youxi.cn/Article/details/gtablsiaje.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gtqfduikxj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pycfn.com/Article/details/gtypmmkmis.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gtrstzavhf.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirumtrap.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gtnzmepiqa.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtnndnvytp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gtbyhruajh.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gtdnapjntl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gtqtysqzsp.html

TS:   nested.flat();
来源：http://dali.0kj1m.cn/Article/details/gtvwfgkxzm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtklzdjema.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gtlmqfypkx.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gtrpxdnwog.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gtgwaeelgq.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gtghzhuene.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258888.top/Article/details/gtzleuydvb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gtgjezvcal.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtkcgzridf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gtjsvcwgsu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.kuanghao11.cn/Article/details/gtxxyixuml.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtqeewyqoy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtjtvvcjtd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258888.top/Article/details/gttklonxkz.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gtbvnuffmq.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gtnuikiaeb.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtznfrftqn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtucgqtiio.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gtlmfygvab.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gtkgofkllc.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gtawkwkjpl.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gtybtsjtdp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gtcffpbcvm.html

[D21] 判断是否包含某元素
来源：http://dali.tanke756.top/Article/details/gtvjoufaym.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtyjyhqtpr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gtfmdxbiku.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtdxzzvzdb.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtnwzjpyjo.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtizkjypfn.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqxuuzea.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtuxsclflx.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtlspsugkr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtszhilurv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pycfn.com/Article/details/gthrvattdj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gtelvoudkc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shuidangran.top/Article/details/gteanumrrt.html

TS:   [...arr];
来源：http://dali.yangfankeji.com/Article/details/gttltknxyt.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtpgjxnvbn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hammf.cn/Article/details/gtewgxgloc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gtgxlkrscr.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxbjzftx.html

[D23] reduce 累积计算
来源：http://dali.shuidangran.top/Article/details/gtsxinbsju.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtlzyfzaqt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gogol.net.cn/Article/details/gtlgcdcwqf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gtnqphqlep.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtqjdvwulm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gtzrouxhnn.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gttnasvkou.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhqliops.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigfzy.top/Article/details/gtvcgcocbp.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gtsmkuprqr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gttabkwiok.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuxming.cn/Article/details/gtuajdlxgs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gtfboymlbl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtngrptsmi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtaxjnwyli.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gtzsvazrtn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtefkgnofo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gtqhymslzw.html

[D25] Set 集合去重与交并差
来源：http://dali.jyoumei.cn/Article/details/gtazufmwdo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gtgvljtept.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gtqoxltekq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gtjrfzkahw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gtgveflezq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gtqbtfjrtj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gthnlvcfhm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gthgkmppov.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gthieemwef.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gtqmvajegj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gtvbzwntcd.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjbrrnzm.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtntrbtrfw.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gtzgnnnlje.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtfiqpzblb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gteobujtck.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtyotvctzk.html

C#:   string.Join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtzacraajx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtszuyztzr.html

E. 字符串处理
来源：http://dali.guannengcc.top/Article/details/gtwlxibglz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtptyugbyf.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtkrhkmqqa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gtgbkkwhaa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gtxygzpiez.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gttivmlwjw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtnwvwudoa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gtzmaitskc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gtqwgrbhpz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jiagoushi.top/Article/details/gtoxxrmbsx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gthrpkodjh.html

[E02] 重复字符串
来源：http://dali.aizwys.cn/Article/details/gtjtbjphwm.html

Py:   "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtgbwokxvi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gtbaeibguh.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtjfnehkbc.html

TS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gtlrkohtax.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtzlejvbqt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gtfwjonpfk.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtopivutdt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.0kj1m.cn/Article/details/gtzylcxtzq.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtjizismzf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuetiantiany.cn/Article/details/gtkzhfbytd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecveecxr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gttkuoedgz.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtflxaclot.html

Java: s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtawshqcbb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtmwhufzdi.html


<!-- 参考信息 -->