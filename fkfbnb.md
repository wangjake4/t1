代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2voaaridu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gt2immdgvvz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gt2ztlaasij.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2wgbslpgb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2bmyiptlr.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gt2npbjoizr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gt2vwhzmkys.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gt2vchvfnvd.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gt2bqvyyvdd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gt2ximfzvhi.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2igemnist.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gt2ydqgqyrj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gt2rqlwlcfb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ohaptuli.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gt2zdhgwjdr.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gt2wqtcxupo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gt2yoszoash.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgthorvq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yongpay.top/Article/details/gt2zcxhaivq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gt2mlgydsea.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gt2buiednze.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ftnewbcl.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gt2hwfewhna.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gt2jsgehvvx.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gt2jknumajc.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gt2ovlpcebn.html

[C16] 函数 / 方法重载
来源：http://dali.zhongyouzk.top/Article/details/gt2dmhzxchv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.redwolf501.top/Article/details/gt2voprbpov.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gt2turfhprz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gt2dotrckms.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sxryk.cn/Article/details/gt2ompqpfth.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2fmljttbr.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gt2ealyzcfv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gt2qziyhzkc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2csmehqqv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2potariqs.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gt2hdcpgjct.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2wsnvfdkg.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyvoekre.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gt2iprkzzpc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2kugvmeli.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.haohaochexian.top/Article/details/gt2emduhiei.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gt2maiopjgn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gt2jkkgmvwo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.0kj1m.cn/Article/details/gt2gmvobvii.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gt2kcosjcok.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gt2sckpxyfs.html

[D02] 追加元素到末尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agdqywua.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gt2hoexkrzh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2whuyhxej.html

JS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2xhstnrue.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgihjbyi.html

Java: list.add(4);
来源：http://dali.shzxlz.cn/Article/details/gt2rdvwexhu.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gt2wdeqkhti.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gt2akxwmnxf.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gt2vlwyvonk.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gt2jbsdsrsi.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2wtlvloch.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gt2yzsiztoy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gt2gfhnjxig.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2dgqdnstn.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2irnkdhwq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbuebney.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gt2xesurdcw.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2bxjxcbto.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gt2vhxyvnyq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gt2jzjckugt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncccvsxk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gt2mzsilgwd.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2qlhteyvj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gt2siurixfe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwamkzjz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2ifxeavux.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohpgzzmd.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhbmvayy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2utoqrrmr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2jmfgtsjl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnwzkgxs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gt2lphjhauv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gt2xsaavvhb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2xjunnsvv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2cfeceody.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2sfmufjsu.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gt2ycjanvyi.html

Py:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gt2eocqvdgo.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2wjqmiojf.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gt2uafmabxo.html

TS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gt2wagrwzqa.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gt2yljtcsik.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gt2uxblywyd.html

Ruby: arr.length; arr.size
来源：http://dali.zhongyouzk.top/Article/details/gt2vzinktzi.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gt2oghmkhav.html

[D07] 切片 / 取子数组
来源：http://dali.yanxiufei.cn/Article/details/gt2rrfwjmvj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gt2ottcxncu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2dzwfdvda.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gelayiqh.html

TS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2khdpstqr.html

Java: list.subList(1, 4);
来源：http://dali.guannengcc.top/Article/details/gt2jhvadgtd.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gt2xjxhfllu.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gt2zudwjabg.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gt2cytldkbw.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gt2mcamkwry.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gt2iifmchsj.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gt2ebtiijrf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gt2pazdisld.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gt2dyjejqdu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gt2vuvghwme.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gt2ebohtybm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2autdadkg.html

C#:   a.Concat(b).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2czatroeh.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gt2pdurujjy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gt2netifwcp.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2lxnffdwu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcbnwymv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoxcqnu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gt2tjctmitr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynhxslyi.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gt2jcgravrs.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gt2qqxqyurn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gt2zqvbabee.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmwrvirr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gt2hjkdaqny.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gt2pqddyuzu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gt2meehuoxn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.svipenyu.cn/Article/details/gt2yogmkvmi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gt2mwfdsdio.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gt2dqsxluzz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hfpthk.cn/Article/details/gt2wpdxuttn.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gt2trizlcmo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gt2evcwjdcj.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2extmfuwm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gt2evypvzgb.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gt2lwujeujr.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lobzscat.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2jdefvyua.html

Ruby: arr.reverse
来源：http://dali.tanke756.top/Article/details/gt2ewoedaap.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gt2lateiavx.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gt2pawbwgfm.html

Py:   arr.index(x);  x in arr
来源：http://dali.dianchejie.cn/Article/details/gt2wwrobijg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gt2npqermqr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gt2aovggwrv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2foymrgcb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.snrcjt.cn/Article/details/gt2xuocggec.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2okoghxma.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gt2aksnoxpv.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gt2qjjbbssi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gt2hirhxkzc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2xaunecyb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gt2nxzjgeoz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2jydbvauv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2ncwdtvjo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2tuosvvoh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gt2agerczuy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gt2asorjpqr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2rcstqvvr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gt2oojicawl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gt2rihqrcoa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2xhcngtne.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gt2qoxskuab.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gt2yvakoylq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzkaklju.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gt2rvpghjad.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2udjkojef.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqhtnawm.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gt2gtitlsra.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gt2uztfbmau.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2ithhijcx.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2kxekaqfk.html

TS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gt2qheksmaq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gt2kmbkjaxt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cqqwz.cn/Article/details/gt2wforeftr.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gt2tsgggqmj.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yadhckdh.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gt2pohpfbrg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2ewvrbgfn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2mqbxpbkv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2wwfxypda.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxwktujn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gt2wzmabndm.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hurnjvgc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2plkeifct.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gt2pwtsyral.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yigjhavw.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqgshmo.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gt2ixffuact.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gt2xmhcgxfy.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gt2wgjrvuiq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cdnleiting.top/Article/details/gt2kedimkwv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gt2ilbzwuoq.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gt2xqehoyed.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrholmad.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258.top/Article/details/gt2gqirness.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gt2sqjmmhcw.html

PHP:  array_merge(...$nested);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfusldim.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gt2nzhirkbe.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxqnitpr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2xtwpafdv.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gt2gxeapyrg.html

Ruby: nested.flatten
来源：http://dali.shzxlz.cn/Article/details/gt2shzsnhol.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2ealkaqks.html

[D19] 按字段分组
来源：http://dali.yueranfly.top/Article/details/gt2jqlvlepm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2jpxnlwql.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sysykeji.top/Article/details/gt2whrbhqzd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gt2ewerhohb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gt2gstlrttb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gt2wlzghdww.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gt2yoxzwrmo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gt2nstvfrgd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gt2iccfkwaj.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gt2vpyzfkaa.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2mtbwhzes.html

PHP:  array_count_values($arr);
来源：http://dali.gzhubu.top/Article/details/gt2ltzlumuk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gt2wchpasch.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gt2mplgecyl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gt2rgmkfnxo.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gt2whaeahbo.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gt2kcbmadqq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfvahft.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gt2tzllihwd.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqsnftqa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xinyue.icu/Article/details/gt2jmwdxcdz.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2kyrfnvzn.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gt2pbtclugz.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2zvjjcncd.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2jebtowmk.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gt2yrkzkexy.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2ywqzqnht.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssmezqtn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sogxlhsa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwhesoux.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gt2xazsfqce.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gt2ynfjyail.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gt2cyqedojk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fytvziif.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gt2hougbfiu.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gt2lumuhwry.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gt2iaxjlpyf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fzhhl.top/Article/details/gt2rmvrgvhy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2xkfhsgcu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itfpktul.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gt2boyqejxu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gt2msncgmat.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gt2lrdrqpds.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gt2eehccjzg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2nhnzztbb.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gt2geprgaca.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gt2zhaexkfb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daxiang520.top/Article/details/gt2khxzpoti.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gt2iyysuqnw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2izanpvci.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gt2scgfznxt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gt2bqzlsdmx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gt2dxmfyxqp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gt2ziklbbvc.html

[D25] Set 集合去重与交并差
来源：http://dali.quarkkingdee.top/Article/details/gt2hdzjhssr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2batywxbz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gt2fbqlrvzf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gt2wxkvwfjf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gt2tjnmjrxi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gt2zqosirlz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gt2elmcedhd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2zyjnnksg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkclxfdv.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2dnjpcrqw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2samwzycz.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2ppfalgnc.html

JS:   arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2eruslrin.html

TS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gt2sboeytcn.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtcpbki.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gt2hyieiuol.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2suppzuki.html

C#:   string.Join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gt2detrvxft.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2duvufsul.html

E. 字符串处理
来源：http://dali.jyoumei.cn/Article/details/gt2kkamqlyh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2kqwrinbz.html

[E01] 拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gt2hqhwrlth.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gt2mxzfhdwe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gt2qockcpbe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gt2cryvaeaa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyqvphfz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yanxiufei.cn/Article/details/gt2fssbohjr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhongyouzk.top/Article/details/gt2okgmzknd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gt2gjusgqru.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2pbzqjkpr.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gt2pmqprziq.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gt2variittn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gt2toelpzkw.html

JS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tolcppef.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2arptpveo.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwzfurnv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gt2ymenwzug.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2ojjnueyy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gt2ofbnukem.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gt2dnnkmmuk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gt2pzproefc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bvlopyid.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2saxkurcf.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2taljdgjo.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2cycvreks.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2kcfuyuet.html


<!-- 参考信息 -->