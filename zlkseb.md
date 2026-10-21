代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.iojbl.cn/Article/details/gtsktwnxom.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtrrwwuktd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.0kj1m.cn/Article/details/gtemcnrpyi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtllxkkmte.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgppgvxmy.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtsmwnbtpp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtdfvfvket.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gtdsouefpm.html

[C14] 泛型函数
来源：http://dali.shuidangran.top/Article/details/gtixsezvqa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cheryme.top/Article/details/gttdnczocq.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtjzwuywfg.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtrrkhlkkc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gtlqeezlfp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gtgyehbtfr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtanflstfv.html

Ruby: # 无泛型
来源：http://dali.birdmap.top/Article/details/gtpcnhjumk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gthpnjuwld.html

[C15] 解构 / 展开参数
来源：http://dali.wangdashe.top/Article/details/gthusbprkq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gtxtehdfvv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yvedp.cn/Article/details/gtuuhdoshm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsoqevvzy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gtrwstbkdm.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gthxprkmlj.html

Go:   // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtjpaclwuh.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gtyqqkmkbz.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtrfmkusnz.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtkpdddacq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuxming.cn/Article/details/gtbkyveerd.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gtpxtqpzag.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guowangkeji.top/Article/details/gthbarudfc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gtukpzsnnf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gtbtrpjdcv.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtwvhxmzni.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gtgcwurzoe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtavozsexr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttersaqxz.html

D. 数组 / 列表 / 集合
来源：http://dali.ivvv.top/Article/details/gtbcbfvtmq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvrebory.html

[D01] 创建数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtobjlxbgu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtdcjkcnei.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtlqrfuqog.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtjrnqdrvk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.vqdsnc.cn/Article/details/gtazpirvhm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtqebmdqff.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gtoyvqrxwc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gtqtpqykbd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gtzrzgybov.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtzbhdtpyo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gthomiunml.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtzulaqxeg.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzbmeazw.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtzyshspmj.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gtocakiobx.html

Go:   arr = append(arr, 4)
来源：http://dali.hnqzz.top/Article/details/gtrzdsqzsj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jianghu66.top/Article/details/gtbjptxzgj.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtgdbatrbb.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gtmktmscpf.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtfuqxzmko.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gtutwuqzca.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gtqusgcbfd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtkwvqrzkw.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gthowtkoye.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gteiiioekr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jyoumei.cn/Article/details/gtonrdmtih.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtzjktidak.html

[D04] 删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetftzvpk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shzxlz.cn/Article/details/gtqososcwl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gtdtwgraey.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gtezsaribt.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gteskqnstq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtrgskszql.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yangfankeji.com/Article/details/gtoucdwrvx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtonmickng.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gogol.net.cn/Article/details/gtawatjbxo.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtznpiuvxm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtlmiblhlm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtuomubkme.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtrrnawcjw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gtbleayvgk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gtdyvhjsnx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtuowzmjnw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtfgwtemvu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtbyzjlqyh.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtcykcyfrd.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtbwssvent.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtdfxjqeng.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtbwcwlxlw.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtbfgoekux.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gtoqztwcbn.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtrkfyefeg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtbyqyjfmz.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gtnpdnqvdw.html

[D07] 切片 / 取子数组
来源：http://dali.hnxiangtu.top/Article/details/gtvoiltzbr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gtuyeuzwaa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtgxoxnkmq.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtowybboxy.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtaaspfstn.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrvzbxrn.html

Go:   arr[1:4]
来源：http://dali.fzhhl.top/Article/details/gtgjtalvso.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtixbynpnv.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtodiokqom.html

[D08] 合并两个数组
来源：http://dali.xylfe.cn/Article/details/gtcyficjaw.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gtjlipvlko.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gtjzuujpwp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hywenlv.cn/Article/details/gtwjsphqci.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsjesylj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gtzntosdfe.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gtkdkfyipr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gtaignhejt.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtvgqqlmbp.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gtavehambn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtgmyyatmw.html

PHP:  sort($arr);
来源：http://dali.yuanzhike.top/Article/details/gtolbteyks.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gtjeweccrn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gtfiakvdti.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hfpthk.cn/Article/details/gtuhoeabrt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtbiiusrtp.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gttlctspiw.html

C#:   list.Sort();
来源：http://dali.cdnleiting.top/Article/details/gtkbygnhub.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtwanjmqpf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gtipyrfhkg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gthsfwxbkj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtbnibbsop.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtiyuiwjzh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258888.top/Article/details/gtapxqqtfe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sxryk.cn/Article/details/gtozajlmro.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gtvabhhjsm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gtgkpwsqoj.html

[D11] 反转数组
来源：http://dali.9152youxi.cn/Article/details/gtxprxyhkj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gtilsqvuia.html

PHP:  array_reverse($arr);
来源：http://dali.hnxiangtu.top/Article/details/gthouemkpu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gtrqenzcwj.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gthjaqsjpo.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gttmxilppv.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtumntslda.html

Ruby: arr.reverse
来源：http://dali.xuanzx.com/Article/details/gtxagajfun.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gtvqfhtlvj.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gtstoavvnc.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtawndhyvf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hammf.cn/Article/details/gtnyzkeyny.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtsxfjlpxo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtqipmojcf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yonumen.top/Article/details/gtmbrdwygr.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtypepdlbp.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtltcanpar.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gtcsfxwjmm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gteueyofzt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cashguo.top/Article/details/gtocjrvnyz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shuidangran.top/Article/details/gtcliopklz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtoxqoijdb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gtdqvfjwzd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gtklmjqjfp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gtwdvjphrc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gtldvvsaub.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtavtxnnbp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gtfvxmscng.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtdmzhefzv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gtuptcipqk.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtzjarcisw.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtmpmxechi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtzelogdjj.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtobfllhes.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtjypepmku.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtxlpitxoh.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gtsniymttk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtomtmhoti.html

PHP:  array_unique($arr);
来源：http://dali.316326.xyz/Article/details/gtvutnvykx.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtbvuojgqb.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gthnsnxxjr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtcitdyneb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtnrqsusix.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gtxothwfgw.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gtpnxyqxdn.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtgycczytp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtninwlyma.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtlovekgqg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtnjnvelci.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtjjfkyrjz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gtlzepwrvm.html

Go:   // 手写循环累加
来源：http://dali.vqdsnc.cn/Article/details/gturfwucpy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbuyeibh.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gtjrqpncjl.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtawxviymf.html

Py:   max(arr);  min(arr)
来源：http://dali.gzhubu.top/Article/details/gtjulgkoqt.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gtdnisuxqw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtkvntygpk.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gtltrzfbbq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gtqkcklptv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtoztkpotr.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gtjfzklimi.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gtcjsuhhai.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gtwrcbsqdu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gtgmzrhuah.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtxuawyxfd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gtepbrsqhd.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnvdzkdx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gtfmyiuoxq.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gthenwphsa.html

Ruby: nested.flatten
来源：http://dali.zhoulong.xyz/Article/details/gtlxgqkqsf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtsxrklplt.html

[D19] 按字段分组
来源：http://dali.xinyue.icu/Article/details/gtwzhcnalk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gtupdeyuga.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gtvcubeifc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fengsongda.top/Article/details/gtdvkkpcwj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtawqdkzyl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.redwolf501.top/Article/details/gtssawiaor.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gtjogtfdpx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtkzzlqskf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gtbqgzxrwp.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvzyjnkn.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gtsqitsidv.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gtlhkthbsw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtslxdnbjl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtbkmraazq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvueguofm.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtwwjnwind.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtyxggutrq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gtmnpxfwei.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gtwyicyfwv.html

Py:   x in arr
来源：http://dali.guowangkeji.top/Article/details/gtzgczrlcz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gtehchgqjg.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtzrxtyyue.html

TS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtazanoxdr.html

Java: list.contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtzkmjgmla.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtimezwcku.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gtmxsogcpc.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtttlyyoew.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gtquvoewre.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gtxrpkamke.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlflgnypw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gtstjpwyxx.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gtkggzgqqc.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gtqpdwwqgj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gtfxkarqto.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gtkxwgfjtb.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gtmabvippz.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtepdthbps.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gtsrmenekc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gtauiapfav.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtnezkbxyj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtdpttfkyb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gtkfzbjvqa.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gtvkmcjrcw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gogol.net.cn/Article/details/gtojvkfivo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtpmbdvymy.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gtziyanshs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yueranfly.top/Article/details/gtisaodwwg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtxvqoalxy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxuanxn.top/Article/details/gteervspmz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gttneabazk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtutroewfr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenjidiqi.icu/Article/details/gtvjqgkjwq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtkxggvrrc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gtdxcmolgz.html

[D25] Set 集合去重与交并差
来源：http://dali.gogol.net.cn/Article/details/gtmthshahs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnpuopmx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gtkzkudwwn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gtdqgdjplv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gtztrphziw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gttpokcfsz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gtwwlqbaje.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shuidangran.top/Article/details/gtubwjivqj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtjdwfssui.html

[D26] 数组转字符串
来源：http://dali.xinyue.icu/Article/details/gtekiwnugo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gtwsswhucl.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtnagkrnzy.html

JS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtpzxrpbgd.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtlplvquuc.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtooahfkea.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gtkioydmmp.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtggwkurbc.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttztguwfk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgyiaclom.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gtmtdbcqns.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkthszhvq.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtflspxrpe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gtcmfajovd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gtoqmbvtzq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gtgvtvmfpw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtbfjpgetq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gthbjozfcd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnqzz.top/Article/details/gtcveablzv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.haohaochexian.top/Article/details/gtppghbktr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtrekpgjcy.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtrppfzgku.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gttoqbaezu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtvxwfjeuh.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtefghznkp.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtqhqfqtpu.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtcvyrnkoh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hammf.cn/Article/details/gtmqhysodo.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtxenqmoyq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gtmdtxuhjw.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtytkkeaoq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.iojbl.cn/Article/details/gtwbhnarcw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtjiguokbm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtdqwaehax.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gttxdriper.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gttomtcdak.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jiagoushi.top/Article/details/gtgfavppte.html


<!-- 参考信息 -->