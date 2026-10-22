代发 wailian999

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gt2cswqmpem.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gt2jekzlsbh.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2tihbxasr.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2evhmebro.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gt2afcjsqxf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gt2rdacdlrt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gt2adzzkiqi.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gt2erepyhox.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gt2szhspvol.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gt2ololmyox.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gt2iffklnnv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngknypld.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gt2rlkojqdu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2bmpnifjg.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gt2cokawosp.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gt2yyfchrju.html

Ruby: a, b = pair
来源：http://dali.aibaodan.cn/Article/details/gt2msxlhchc.html

C#:   var (a, b) = pair;
来源：http://dali.smart0.xyz/Article/details/gt2jmuqyguo.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gt2jwrhsdgh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gt2fswfosrf.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gt2cejxrocc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sinnlpwx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcpevgtf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gt2wpwaiiss.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gt2ebwmqeem.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gt2cbcuistg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gt2kxfopzrw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ltuwxnph.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gt2ljkfetap.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2shqkvlvb.html

[D01] 创建数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gt2fzzwjorz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gt2gmkljquv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gt2ifejhcow.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jiagoushi.top/Article/details/gt2ssrgyqxz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gt2dsrkvftp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gt2azmfmoos.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gt2nmzhafsj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gt2pibvahcz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yonumen.top/Article/details/gt2wqpwkqdu.html

[D02] 追加元素到末尾
来源：http://dali.hnxiangtu.top/Article/details/gt2vfwwrape.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangdashe.top/Article/details/gt2paqjwpls.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gt2knmbogxt.html

JS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gt2qmjymtfe.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gt2ztqiuywt.html

Java: list.add(4);
来源：http://dali.aizwys.cn/Article/details/gt2whmgrctd.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2tlugvozl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gt2vctzukam.html

C#:   list.Add(4);
来源：http://dali.hysaishi.cn/Article/details/gt2qnllptxj.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gt2dlllkpls.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2wixoirip.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gt2wjlscdxz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cdnleiting.top/Article/details/gt2vqmmhvfy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2rqxuetxe.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2uuqxhukv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gt2urogdufa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gt2smivlnop.html

C#:   list.Insert(0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2cecmpral.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hsigceqq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2zbyisuvi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2zecfylau.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnbxirna.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gt2kwbmgkyl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gt2coqzikni.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gt2tbniritv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gt2wtqxoysg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj202588.top/Article/details/gt2aqycfqba.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gt2dephsaoc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2rezpkgna.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txesxpng.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2bnpurbce.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gt2btcnmfcf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgvamfy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gt2cppjgfnf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2xpqnzdzr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2gdxwaxrs.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gt2rlmpmior.html

Py:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2nrrmnnpm.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gt2xcbmmeqo.html

JS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gt2beyxucba.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gt2lmwyijec.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gt2qjkimosn.html

Go:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gt2kmqtkmbr.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gt2wjrtoqqc.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gt2adcoypjx.html

[D07] 切片 / 取子数组
来源：http://dali.gzhubu.top/Article/details/gt2okssmqyk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkciljfn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2izxmrybg.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2gymuzxke.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2vlxjkprm.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtoxqcmu.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gt2gycwxpaj.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gt2xzbjujjk.html

C#:   list.GetRange(1, 3);
来源：http://dali.birdmap.top/Article/details/gt2hmfexefi.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gt2zyvnxmuv.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gt2egsijnlb.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gt2lbbpuisg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gt2vpnulqyc.html

TS:   [...a, ...b];
来源：http://dali.jyoumei.cn/Article/details/gt2ozuaztyv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2nnsdjuvt.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofyomepr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gt2nkggiosb.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2tedgsglm.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wluelmzf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lotpixzc.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gt2qyyzewfl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gt2eokthmrw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tian-w.cn/Article/details/gt2tfyhyxdv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gt2whfzbtiw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gt2mjuwpnnk.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnzgnuqx.html

C#:   list.Sort();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uuflauet.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gt2cmpnwhhy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gt2gijaiazd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gt2jqeguwif.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvgeqxqp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2ercycjbq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkzmxgjv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxwpgmtz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gt2knystrkw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gt2brdjjzwc.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddzdfajp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ybcxt.top/Article/details/gt2imndqznn.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2ypzhngce.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ybcxt.top/Article/details/gt2gugtixsu.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gt2qhkmsbqy.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztkmmgzl.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gt2xgbteery.html

Ruby: arr.reverse
来源：http://dali.daria6918.cn/Article/details/gt2ghytozuf.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gt2aeozicjt.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gt2tqldoufi.html

Py:   arr.index(x);  x in arr
来源：http://dali.guannengcc.top/Article/details/gt2fpcqzkvq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xozrvwqj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2wsqnuagd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2ntdbhtvd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gt2tnqqxqyb.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2nfkqutnv.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gt2sgrwalyx.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gt2dlbvljvl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gt2fbswsvoc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ppjwa.cn/Article/details/gt2dojgcxsw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gt2ssvvduol.html

JS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2ytnidpeg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2uvszoyim.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gt2rtrckvhu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gt2azyidpva.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gt2edjzqrrx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2jwimjeaz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yvedp.cn/Article/details/gt2znvjyinl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2zalxrejl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gt2cmtvyizt.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gt2gjygxobl.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gt2lmkylyxl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gt2piyulnfn.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2dildhrat.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2tyddpwkq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2yfioxnig.html

[D15] 去重
来源：http://dali.0kj1m.cn/Article/details/gt2ubtecbij.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gt2wfwajlan.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gt2ezqnrcsj.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2dhityhrx.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2xgutcjyb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhjysiuy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdvmgiiw.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gt2zavvczgl.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gt2vgoozkae.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psdjpfvi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2ncqtydof.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gt2yplblxtz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2lbunqiki.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2eyhbbjki.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gt2kgmkheaj.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gt2mgomdwuj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258888.top/Article/details/gt2btjumvme.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gt2qvekwqad.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gt2imqhixbb.html

Py:   max(arr);  min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2jgrsqoiy.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2bymcakpd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2wijxzguu.html

TS:   Math.max(...arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwiwduda.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gt2jgomigcg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2bvcongqk.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gt2nbclpokv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yudaojng.html

[D18] 扁平化嵌套数组
来源：http://dali.quarkkingdee.top/Article/details/gt2aixbfalx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gt2aqmlmpin.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gt2hluvjqrv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gt2wudvvwuz.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptzvogtj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2znrimwos.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gt2sheyuxfj.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gt2fzzuefqy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2oxzyusgs.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2yaexfxky.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2hqtlmjgo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gogol.net.cn/Article/details/gt2mocjfshs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gt2mhlxoqff.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gt2atbvxuzr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tanke756.top/Article/details/gt2opjmjunk.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gt2pzcwnnem.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gt2xmuupboc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gt2lyahuadi.html

[D20] 统计每个元素出现次数
来源：http://dali.redwolf501.top/Article/details/gt2evoiwmse.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2jmmdwbxg.html

PHP:  array_count_values($arr);
来源：http://dali.c1oappe.top/Article/details/gt2obsowlzo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2xyegjjow.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gt2hvwjxjsl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gt2wieyxgeg.html

Go:   // 手写 map[T]int
来源：http://dali.tian-w.cn/Article/details/gt2ybneqjbi.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gt2mauqnmmf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gt2nvkbseay.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gt2lxlkepjt.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2urpabmfw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2euypolvw.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2kuvogzqy.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2eogkmbri.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2kbjsfsxo.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2fwpsfrsq.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gt2imxlpvdg.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2didwvdqi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gt2tozqwqpm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gt2xapuckuj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjfbnaiy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aizwys.cn/Article/details/gt2jjyiowmo.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gt2tzpfojwe.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcrdysng.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwpkfwxh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gt2lryxhvce.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gt2myrstgds.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gt2wthndxgn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gt2wlzzfkwm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtxxnsdd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2oatbfizy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpyxmfan.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gt2qjbubugp.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gt2qqveetvg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gt2ntymgaxg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfmnpoyn.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gt2ckmvgnye.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjtlrqvn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gt2sovezkmk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbicvzgc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2afkyttwr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gt2dgsjjixf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gt2epaczptz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gt2jnefjisw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gt2mjqjbmlg.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gt2ubuvseha.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xinyue.icu/Article/details/gt2eqjhtbsx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gt2offrkkza.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gt2iachzxln.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shuidangran.top/Article/details/gt2vdzuycrw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gt2njzzlfvf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehvogcrz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gt2uqcxwxwq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnqzz.top/Article/details/gt2zffwoxai.html

[D26] 数组转字符串
来源：http://dali.redwolf501.top/Article/details/gt2diwtxhak.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2hxahjsaa.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2njgyhamv.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2fhnfmyfk.html

TS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2iypqzwta.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2lpkqdoio.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsrbfacd.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2odahisnc.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gt2iifvggbb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2coislddc.html

E. 字符串处理
来源：http://dali.xziqi.cn/Article/details/gt2rmeabeva.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvbcwauc.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2grjrrlqf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.haohaochexian.top/Article/details/gt2gbhksxyq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cashguo.top/Article/details/gt2burlfvbj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gt2eidjqgbr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gt2jkisbsoj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gt2gzlhaygs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2aiobmeoz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.meibo888.top/Article/details/gt2nhsnfbma.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbokcvkc.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gt2wkurmvet.html

Py:   "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrufluym.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gt2lxagsedz.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gt2badgkflf.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfqtwbpw.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgpsnree.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2syvaemvr.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gt2twnutrqg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gt2ugwhcocq.html

[E03] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xaorntyk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytnxnudd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2voblxpuk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.birdmap.top/Article/details/gt2ibtqwdgz.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2vypahmzz.html

Java: s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2icsuyxfi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gt2vljnpqok.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gt2gtdmckjl.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gt2hxizrkwn.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gt2quvqjzwh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gt2shluqudn.html

PHP:  strpos($s, "x");
来源：http://dali.sufxvd.cn/Article/details/gt2sgsiuuen.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gt2lqtpzoaj.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2agtokcfz.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gt2ujvvotyq.html


<!-- 参考信息 -->