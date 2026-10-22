代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gtxdqlgwru.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtrvolctku.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtmmpftdxm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtooevgoio.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtwxycodte.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtvzimrueb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gtxzxtsyco.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gtnxahafzd.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gtnnikglfn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ehwqpu.com/Article/details/gtnliqjlol.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gttdevwoib.html

JS:   // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtagninenr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gtsmzxlszi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gtfabdkiqu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gtklhviozx.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gtypnllzbm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gtlscawqtr.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gttasroyse.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gtukgscepw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gtgbdywhoz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtfavhqywq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gtrabixspi.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtgxkoewbj.html

Go:   // 无解构
来源：http://dali.ydzc1.top/Article/details/gtufflggtj.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gtkofymsdu.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gtjmjqkwqe.html

[C16] 函数 / 方法重载
来源：http://dali.xinyue.icu/Article/details/gtxxfptzbg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gtbtkkjviw.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtavfezmoq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gtibtjjdcu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftriwvlw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtyzujmgth.html

Go:   // 无重载：用不同函数名
来源：http://dali.jlsjyb.cn/Article/details/gtruwbweyy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gttzzorftz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiwonqri.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkjboyedw.html

D. 数组 / 列表 / 集合
来源：http://dali.cucudq.cn/Article/details/gtnbkmzvsw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttjlhqhmy.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtpbsbcsfr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gthwqvtltt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yongpay.top/Article/details/gtfajhvwvm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtecgauoly.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shangyingyoupin.top/Article/details/gtsylzfrym.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gthuvdlqgj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpzcrduj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gtfpxofivu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtngtolmfs.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gtzxkocidq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gtgzskyxah.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtusvcjpai.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtbkjcixtg.html

TS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtaakwuwsh.html

Java: list.add(4);
来源：http://dali.sysykeji.top/Article/details/gtxjbslrsd.html

Go:   arr = append(arr, 4)
来源：http://dali.dashuyun.cn/Article/details/gtkdsuijif.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gtyzudfctd.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtynprczmx.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcqnkwao.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtoqopehem.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqczprlwv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.quarkkingdee.top/Article/details/gtyletxrsq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daxiang520.top/Article/details/gtidcdxwey.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtktabjsou.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtfgtnfgnw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuxming.cn/Article/details/gtuiamzmza.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtjdnjnsya.html

[D04] 删除元素
来源：http://dali.316326.xyz/Article/details/gthjnlyqjp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtgikkpmbs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ybcxt.top/Article/details/gtoxcuzqgo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gtfyigxbja.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gtfdktwtcx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtaqsmdlpo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daria6918.cn/Article/details/gtkxalfjmw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtgagwgbjo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtaauvmelm.html

[D05] 访问与修改元素
来源：http://dali.snrcjt.cn/Article/details/gtdlroulks.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtengslakm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtenbwgehl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gthxhqccbl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gtkfpfrriy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmswqpuij.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtlgimlepf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtyhhkvcku.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtfaeqdrvj.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtfvlwddfb.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtkmmqpztq.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtsjriffwk.html

JS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gttprbpoyf.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtfomnperq.html

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gtszcgxhbg.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtnjpauirb.html

Ruby: arr.length; arr.size
来源：http://dali.9152youxi.cn/Article/details/gtohdnabht.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gtotqxhwfz.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gtenwsokfg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gteimfvzjt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtodtgnapf.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtjdxlbecm.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtdurudajx.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtxwlgefjj.html

Go:   arr[1:4]
来源：http://dali.zycfv.cn/Article/details/gtgkokboct.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gtoznwvjfb.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtnulatyrw.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gtvudqssam.html

Py:   a + b;  a.extend(b)
来源：http://dali.xylfe.cn/Article/details/gtmqmjutkg.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gtiabwjxhi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gtqqjmelgn.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gtlfysjsig.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gtcrupmcxl.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gtsxcbgrbi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yueranfly.top/Article/details/gtxawzauaq.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gtvufijmzv.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gtbvcixuic.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtajhnhjxm.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtnlnobion.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gtfyrugzet.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gtjyerdatz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guowangkeji.top/Article/details/gtsfrnigvi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtxfqhfsfv.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gttdunibto.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gtoxfsynst.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gtbxfyxccm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gtweswofka.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtosgkow.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtdxgrrvdt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtqunoyowo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtdvopnwsy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gtyojlyhjq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtqvbbzppg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhixingplan.top/Article/details/gtudzuvgdd.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gtzcdtduuf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sweek.top/Article/details/gtchiwiedk.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gtdathougv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtmdfxvxey.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gtstdkobmu.html

Java: Collections.reverse(list);
来源：http://dali.zhengqikj.top/Article/details/gtpxlmuhyb.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gtpaakpxgk.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtiatziqyo.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtalxwjapo.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gtjpugixsr.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gtznmvbfek.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtqlomfmqi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtpbmgrxkw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtyxeqjchc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hammf.cn/Article/details/gtrwrjcxlr.html

Go:   slices.Index(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtsskcaxaa.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtdcsfvvkt.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gtvhgxpotn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtwsjisisa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtdmzfjblk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gtxqhriwqv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtaelfadre.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtvlhmbryy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gtexngmumf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenzaomai.com/Article/details/gtattynzeo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gtvuwactzw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gtfswamzrh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtmmhclibq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gttjbfwiju.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtnqteidev.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtmsgsdcgg.html

TS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtstuveepy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivznpejd.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtcqjrdqgn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtxqwgguxu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gtbtetggpl.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtlexihhzs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtnkklbqhl.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtarxexerw.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtocclaspx.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtjwwzvewj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gttwhzuwej.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jlsjyb.cn/Article/details/gtylvzyzcr.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gtawuquqvs.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtunrcyjxw.html

[D16] 求和与平均值
来源：http://dali.cashguo.top/Article/details/gtdyhhixqn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtyigmudpi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yongpay.top/Article/details/gtdlzwbbfi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfgmijdx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtnbbwlevl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cqqwz.cn/Article/details/gtpnsvqzhu.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gtyjdadpft.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gtfhipcclm.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssyumcsp.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gtuuhirroz.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtxevwzfcl.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtvstyrvos.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258888.top/Article/details/gtiodxrtyf.html

TS:   Math.max(...arr);
来源：http://dali.wangdashe.top/Article/details/gtaxytdpmr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.snrcjt.cn/Article/details/gtvurkaoua.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtmaoocfeo.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gtvuzhdbul.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gtcvzwhzfp.html

[D18] 扁平化嵌套数组
来源：http://dali.fzhhl.top/Article/details/gtfzpchktc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gtwfcbhyhz.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gtzljarfge.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gtddqtayye.html

TS:   nested.flat();
来源：http://dali.jqgfzy.top/Article/details/gtqsbcruhl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.svipenyu.cn/Article/details/gtcfctrvsg.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gttayllyqa.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gtarzshfkp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtkunnmfbc.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gtzporygft.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gtbxjluyjc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gtoucbovqm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sufxvd.cn/Article/details/gtgkmgpoue.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gttnxiepll.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtouhdioxi.html

Go:   // 手写 map[string][]T
来源：http://dali.jinqigufen.top/Article/details/gtvzihboee.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gtdneepvut.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtfzxbxquz.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gtipzlzudm.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gteseturod.html

PHP:  array_count_values($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrdqrzso.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtmpiiojrh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtldyfvyyo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zycfv.cn/Article/details/gthialtqvb.html

Go:   // 手写 map[T]int
来源：http://dali.cqqwz.cn/Article/details/gtcpljagqn.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gtuiiwauzg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gtonjsbmdd.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gtxsrujqxc.html

Py:   x in arr
来源：http://dali.guannengcc.top/Article/details/gtdzbjauqz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gtnkxspjcw.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtezkpxjes.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtpfnyhthw.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gtrrthxrqb.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtninlfnfq.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gtrushxqhu.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtyfqseqol.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gtqjwsfrix.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gtqepywzbu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gturbsfopm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtpuuctkhl.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gthvcoqiqb.html

Java: new ArrayList<>(list);
来源：http://dali.cqqwz.cn/Article/details/gtipymhume.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtledfjykf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gtwepmnndv.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtuiqvxfhc.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gtxvhwyyuh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gtoouiytga.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtlfstgkli.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtwphkhuik.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtzjbivlls.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.smart0.xyz/Article/details/gtcveyiiny.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtaeiayvrm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gttzgugxmy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hongshengwenyu.top/Article/details/gtmfeqoplo.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtmalxdvas.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gtpxgiquvl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj202588.top/Article/details/gtxvonwszl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gtsynjdebw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtbevzymjx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.svipenyu.cn/Article/details/gtyicbstbz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gtnimqhxah.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gttxmuaktr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gtquwsqdhx.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gtnklzdqne.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gtmeejyvqr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtorllpgsi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gtjrpxpaas.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkeixqxeh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtwpglbruj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryqjmyug.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gteevmdvbl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtbizvlclr.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtzerfuyoy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtxbltnnyj.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtsfdccfat.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtauqfnwnp.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtieizfhym.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtobhqufhn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gtqdvncklr.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbufgqmp.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtghfuwfyt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtglzulraa.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gtpvmjmwmu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthiyidxym.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyqnbqbk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gtfgkojsvf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gtwossiphb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtkiwnnijx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtytmucmvc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gtvfwtbubh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cqqwz.cn/Article/details/gtkitdcpmp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtuxcpvdgp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.c1oappe.top/Article/details/gthezabgan.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gtdjgsyjml.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtnbgacmyj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gthpuzlguj.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gthdufagfk.html

TS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtrqzqvcwr.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtkhudxnfy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.snrcjt.cn/Article/details/gtqzrmoumc.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gthhkzldgw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gtztqceivm.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gthrqnlseo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gtawpjcbeq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtomfumapd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtxskrwlda.html

TS:   s.slice(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtwlcvolav.html

Java: s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gtbkkfxgre.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtktkrdctm.html


<!-- 参考信息 -->