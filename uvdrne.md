代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtwudfmcht.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gtpmqsgtih.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gtrblbcgxw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenjidiqi.icu/Article/details/gtomxkqgbz.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gtgypqfkck.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gtguzamitv.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtlrckztyi.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtwduzztnj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gtkznvaxnn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gthwxhdyth.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gthczjztmw.html

Ruby: # 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtsnvlxzul.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gttgwlmggo.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gtccrudhdl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gtibeciuhe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sweek.top/Article/details/gthitihcgz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gtaufwxect.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtyskfljsv.html

Java: // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtqahigsms.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtjjdmdfbe.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtrmlsttfg.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gtoumlzklp.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gtdwvnrtod.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gtrhadkzaa.html

PHP:  // 无重载
来源：http://dali.yanxiufei.cn/Article/details/gtglfgylba.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gtxnfovimf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gtknlgjehs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gttvyzrdml.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtvpjhkszr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gtltkjeqat.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtexgbkwaq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtljmqmwwl.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gtwjkhkgll.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtoeccjptw.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtiuquhqpy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtnwkxgvqp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtuymzxpij.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtankfzqwu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gttptuuwya.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gtggqxlurr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gtwggqnfym.html

Ruby: arr = [1, 2, 3]
来源：http://dali.bjfxy.top/Article/details/gtjeyuutac.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gtlfujawcl.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gtitpxpqgw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gtnqvigkni.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guannengcc.top/Article/details/gtsmghsfjs.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtijlnimxt.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtnhtumsbr.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gtetavqcae.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtmfmdxhgf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gtfyonosqp.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gtqqyydola.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gtfncafbmd.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtztzvnvlh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gtrzybundv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gtemmanrij.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjetlupwq.html

Java: list.add(0, 0);
来源：http://dali.ivvv.top/Article/details/gtoyavvjkp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gtfzqiorgd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gtkhjrwokc.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtkwvwboif.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gtmrqrcmwf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gtrmzzhmad.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtntarbfsj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gtqxwviwki.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gtoigytjay.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gtgqkbbhwl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shangyingyoupin.top/Article/details/gtdmobpvwu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gtouoxxogc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtpomplikw.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtvqtffbiz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtnwihespt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabrlxqsi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtnphcevpt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gtkpmlomjy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.316326.xyz/Article/details/gtoosgbdxj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtowoupehj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gthvpkhnul.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtpvcbitsl.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtzgatwjmi.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gtynwsvvjz.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gtfkbyycag.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtbeiiavsl.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtiqaxjhcc.html

Java: list.size();
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxvgncmc.html

Go:   len(arr)
来源：http://dali.yj20258.top/Article/details/gtqzbjgpah.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwylznizm.html

C#:   list.Count;
来源：http://dali.zhongyouzk.top/Article/details/gtqorqqhby.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gthvjoyebp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtxjoltjdg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gterhmvhyx.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtkmunpled.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtytjbnqxo.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtrztzwtuq.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gtbzoytubo.html

Ruby: arr[1, 3]
来源：http://dali.gogol.net.cn/Article/details/gtbjbfbmxp.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtioeqallb.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gtmvxrfpmq.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gtyjssozpc.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gtaqxmbwkm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gtxoyuylhl.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gttedmgyvl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtkligcvom.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gtclubgmkk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gtywjrsltv.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtmgyqprob.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gtutdhifkx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtkbspdwuc.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gtmlywymqw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtdcobsajs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gtkwcuywmn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gtwykufsla.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtbwqdgucy.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtoqjpfqaf.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gtepzqhsbo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gtsxzgfxmg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gtoassljzt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtzqxdfffj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gthxmiqyus.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtzhhkdtqm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gtpeaeukyu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gttemckitq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gtvomzychn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gtfqcnioom.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gtclimmzrd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gtqwrfxffp.html

PHP:  array_reverse($arr);
来源：http://dali.yuanzhike.top/Article/details/gthwmoyrvm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gttdasiigw.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtolobxmhu.html

Java: Collections.reverse(list);
来源：http://dali.yj20258.top/Article/details/gtargolfkk.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gtlxqdxzfg.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtjktdbgdz.html

C#:   list.Reverse();
来源：http://dali.havefunace.top/Article/details/gteofbxlwg.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gtoiemwrmq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gtqvmmzjwq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gtvgjaoyvv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gthqrnmguj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtitjhfxmi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gthdjyarro.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gtmfcjugli.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gtdmsftdml.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtlkuojkvs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gtlzdebprt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtuygxutxk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtskghscfj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtnqltinvr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtnkckudbu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gthrkuhvlz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gtjnepdelu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gtwmqqkrei.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtnpcusdom.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangdashe.top/Article/details/gtsfdcdesr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gtxvorhtyq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gtllrdlntn.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtwzraitjm.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtkltivsks.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtmspgvasw.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gttzvabisb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtdsfesakw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtndipsubx.html

[D15] 去重
来源：http://dali.xziqi.cn/Article/details/gtlswqhedk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtdtqlocec.html

PHP:  array_unique($arr);
来源：http://dali.redwolf501.top/Article/details/gtvervlpny.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtakooniac.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtemjilyje.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gtmgtlvsgk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gtjhvbsnsi.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gtvnckozot.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gteeqhmfrq.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gtbefiekny.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gteuhqcwie.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daria6918.cn/Article/details/gtycftxpte.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtsmkfkoyx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtpfsibvel.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gtmijcplvo.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtudcdjviw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtieatphhb.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtkrkbydkx.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtxlhesiqs.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtpupvahhd.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtqmxazpvo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gttrrzkmve.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtaxlysvgf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokodkabs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gtxfofwoji.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gtkbvhxfxv.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtmgkgeuya.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gtlkxzuqnc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gtfflgnfot.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gtnaoaijta.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtxytywuxb.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gtsawckhrj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzbtxfah.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtmnygcavd.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gtipqpljat.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtjujxurtv.html

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmstcamdv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.redwolf501.top/Article/details/gtwziicjij.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gtaarpxhbe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmbddhdz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtinotslik.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gttikkrzzz.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gtxcqizgvq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jyoumei.cn/Article/details/gttcsewzky.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gtcppuaowa.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gtlefplweo.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gtazinxkiz.html

PHP:  array_count_values($arr);
来源：http://dali.fengsongda.top/Article/details/gtgauefets.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtlkbervcp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtifkcxhxb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtqoyicwqy.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gtstzvgenb.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gtzoalodsn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gtipqmdace.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gtmlockacn.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gtzdjdyfxq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yvedp.cn/Article/details/gtjkviptwb.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjymeisik.html

TS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtsymrttax.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gtkplvbrog.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtdodwmkrh.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gtfojjovbb.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtmguhkdld.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xylfe.cn/Article/details/gtguylular.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gtmwevkovm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gtghxlbmhq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtvxaikqpb.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtxechupzk.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gthvdmyusr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtlkyvnjpc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtglnddvjq.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtljgwrrun.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gtykhslscf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzsmvrye.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtxynskutg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtanigpgsy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtgpyhgmxq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjewcceao.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtytyfjtwf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gttsoigqae.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nanxuanxn.top/Article/details/gthburzrsa.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouwdfxqe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtrsouozzg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jyoumei.cn/Article/details/gtryyeyboz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hywenlv.cn/Article/details/gtcdqdbuhn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtlmgwdrnb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtkudxbkkq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gtijjlrpze.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtgeludwxu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangshuangyany.cn/Article/details/gtsgxzkvlq.html

[D25] Set 集合去重与交并差
来源：http://dali.wangdashe.top/Article/details/gtmzgzwlhr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gtpucpkype.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cashguo.top/Article/details/gtnqepbdey.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtdvujktda.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gtjrhzrvpf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehpnpbck.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtpetqoxfm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gtpypxvroc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gtcpouvlin.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gtmgoqlzcj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gthlaohqev.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gtcntmwegn.html

JS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtreeiiajn.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtnjxukprg.html

Java: String.join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsieshdp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gtbsqqgtzq.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtvnqgqrvy.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtbvbfgudt.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlvlfurhk.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gtanamuufw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdfyjlgyv.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtvczwbkgu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gtpslvepte.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gtaxqblcpd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtadccbgov.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtmdbcterr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gteydemxdu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gtxhzntwgl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yongpay.top/Article/details/gtubrqrvbt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtaegvtsij.html

[E02] 重复字符串
来源：http://dali.ybcxt.top/Article/details/gtsxrkurlj.html

Py:   "ab" * 3
来源：http://dali.zhongyouzk.top/Article/details/gttakkgecv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangdashe.top/Article/details/gtglfknxwi.html

JS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtqyiricod.html

TS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtaabsutfo.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gtlguuipno.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtqlfxcagg.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtxzvdtssp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtqvixovhj.html

[E03] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtnakfjkxj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gtcfvobcvx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtfxngjcgt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gttsambtew.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtfbojjhyz.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtgmnjqkik.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gtfbmvwxus.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hnxiangtu.top/Article/details/gtpmriiwbr.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxuanxn.top/Article/details/gtbgoekffm.html

[E04] 查找子串位置
来源：http://dali.jqgfzy.top/Article/details/gtmyxrkery.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtaparxraj.html


<!-- 参考信息 -->