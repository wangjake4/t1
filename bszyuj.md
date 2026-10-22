代发 wailian999

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gt2wpwoedav.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gt2wpbgwemq.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2cynbwgin.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2qnmrmino.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsuxmpup.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2uouxihoj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gt2xifpclag.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2cyipcvov.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gt2tieixqsb.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gt2lrelgpgi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shzxlz.cn/Article/details/gt2dpjkplpw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gt2bfewnqwj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ctbtdyze.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2wjvjsxlf.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gt2kauneyoc.html

Go:   // 无解构
来源：http://dali.zhengqikj.top/Article/details/gt2pjflyuzh.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gt2jorfffht.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gt2wiajqjhf.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gt2zpytrgfz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenlongwang.top/Article/details/gt2gpyrngwj.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gt2hrkdcoml.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gt2qxdanhyj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eaespcul.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gt2bvingyze.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gt2jrfedvix.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gt2dfytmtnt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gt2xbsogdxn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypputzmv.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gt2bhldvvqq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2kayxfhlt.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gt2habvqxir.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jiagoushi.top/Article/details/gt2gpsgyzbl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gt2gvgezzgn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gt2stgjxswn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gt2ihpmfyqc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgufenzy.top/Article/details/gt2eyfxtkph.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gt2asicrmyl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncwxvryi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbxqcwbr.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gt2vemyuduc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.bjfxy.top/Article/details/gt2taqnedsh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2avjczrdb.html

JS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2pclxydpz.html

TS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2vctsrwmk.html

Java: list.add(4);
来源：http://dali.havefunace.top/Article/details/gt2mzigpeuo.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2vtnqsduy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gt2rfjpqgrb.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qewdtomq.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gt2kcvuysci.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxsafltq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gt2jtoiofik.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jlsjyb.cn/Article/details/gt2nosvcmwq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2pjteuujk.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2wfrkwzsj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gt2auofychy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gt2iahmzgmc.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2cxmicvgx.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmrcebxu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yangfankeji.com/Article/details/gt2czbntpsh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2bmarrskm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gt2vmnjozkk.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gt2jpgcnwsf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guannengcc.top/Article/details/gt2fdyluciu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gt2rldbsbxa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2urczilqb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yueranfly.top/Article/details/gt2ghogowht.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gt2psnedusj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2uiaisnfi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2wbbjrrru.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2alffzfhs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tanke756.top/Article/details/gt2nwuwrixc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gt2aeasfbcd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2dplwkvqq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2lznnevab.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtekwwep.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2kpfygwzw.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2jjrelhzq.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gt2kegfldse.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gt2mgkeornt.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2shpcbwjx.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gt2yscelczp.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gt2nhfzdhyj.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gt2pnhjtpwz.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gt2rukkjvlm.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gt2oklgohbr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gt2fdeyglih.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gt2klsmplvt.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2phldxwhs.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2jcrpinfd.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2gbtvbzsm.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gt2xiinbymi.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gt2rytwusaa.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2bjsedpod.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifrlblmh.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gt2yhdcnbng.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gt2peszcpnj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gt2iuuezxbh.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gt2acwpnglo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2wrvqodwd.html

Go:   append(a, b...)
来源：http://dali.ehwqpu.com/Article/details/gt2luhouzlh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guowangkeji.top/Article/details/gt2cupbymcf.html

C#:   a.Concat(b).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2bxdeomom.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gt2unngrwes.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gt2soafbtmc.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eksemjub.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlfxeekc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tian-w.cn/Article/details/gt2snfhckdm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gt2rdmkbmms.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gt2kxlnsxrr.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gt2xkayafcf.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gt2dznlecpj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gt2eztvqdrt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gt2tunvefxy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gt2rqykfebn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gt2xnphoehj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gt2zxvvzysx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gt2nvtxgvmc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gt2refvorxh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gt2ubbkchpb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhpuvbum.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gt2rcasxnto.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gt2ihcsbaqr.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2jttczcun.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.bjfxy.top/Article/details/gt2vljhcykr.html

TS:   [...arr].reverse();
来源：http://dali.jinqigfzy.top/Article/details/gt2xhcgexce.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhgigvbo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nesevzgr.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gt2hvaorfdx.html

C#:   list.Reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhrjuxcu.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gt2cvmfcoxh.html

Py:   arr.index(x);  x in arr
来源：http://dali.dianchejie.cn/Article/details/gt2cdsvaqqm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rejomobm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwawpqtd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2ikdvgjuq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzelrxbz.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2mcmbuwwl.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gt2nluekeku.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gt2wibedxbm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gt2tlsvzuiy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gt2pjjhatrs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gt2qzpeelso.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gt2xxhenhxj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gt2tlpykqpy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gt2vszgdaef.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gt2tmxwlggp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gt2dfakdavz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2vvovzkik.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gt2ohcfwkck.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2ylyrpuwp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ppjwa.cn/Article/details/gt2shmdyesv.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gt2dvouvdxa.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2dffbljpu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2tzfikphr.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gt2ktzydvbf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2pnhhdzrn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pggiidos.html

[D15] 去重
来源：http://dali.havefunace.top/Article/details/gt2qzywlrus.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gt2kqqvezxy.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gt2afxubaof.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gt2ohtgskuu.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2nwummgyp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gt2lltnsuki.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gt2sbqsiqfg.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdwckdnd.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2tgmrjpgz.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gt2yvkfeawx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2gvtddeif.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2jlvruveu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smkaizlh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gt2loxdoqzu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gt2xbbmxwke.html

Go:   // 手写循环累加
来源：http://dali.hammf.cn/Article/details/gt2nbmqerni.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gt2pfgjvcsv.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhoulong.xyz/Article/details/gt2rekyflcq.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gt2jshnpxzf.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gt2dltvbfiq.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gt2bwewdbwk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tojhxeip.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gt2hgduukbo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gt2xxmqzowy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gt2rhokdzwu.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gt2idkofljo.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gt2zscrvxzh.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gt2xxupolbh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gt2ommdxyjs.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gt2jbfzpvvs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258.top/Article/details/gt2rwslybcl.html

TS:   nested.flat();
来源：http://dali.meibo888.top/Article/details/gt2cqyvuswh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gt2bjsptuyx.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2ugsvifjo.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gt2bdwitujk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2angctkjz.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gt2yixvvszf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gt2cjjqaazx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jyoumei.cn/Article/details/gt2xlabfxvv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2xfmipfnq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gt2nxjwafnn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gt2ryinrhmv.html

Go:   // 手写 map[string][]T
来源：http://dali.xylfe.cn/Article/details/gt2kiuhbvjw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gt2kmxbexpo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gt2zygzrvag.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gt2wtfpblaj.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfcrsnjx.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujsewazp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gt2absullfe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2vcjxncvt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gt2zplcfotx.html

Go:   // 手写 map[T]int
来源：http://dali.quarkkingdee.top/Article/details/gt2rlbakvep.html

Ruby: arr.tally
来源：http://dali.ehwqpu.com/Article/details/gt2hvxycfzy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgkduppk.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gt2kuztpons.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2iqtinecq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xinyue.icu/Article/details/gt2ldldnako.html

JS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2uickrdxj.html

TS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gt2gxhgmvyi.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yviedbaa.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2zaildbww.html

Ruby: arr.include?(x)
来源：http://dali.sufxvd.cn/Article/details/gt2bhkdisyn.html

C#:   list.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2lylyibwy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gt2dzxgpyen.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gt2xkpcibfq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gt2moxrevkj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2ztnihcxw.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gt2grmvpigq.html

Java: new ArrayList<>(list);
来源：http://dali.xuanzx.com/Article/details/gt2gacsfqcu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2hzitiaxn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gt2cjoyqtny.html

C#:   new List<int>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ucbgwyjm.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gt2mhhxoaor.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gt2ochcgavv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2bfmjerxq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2hobttcgk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2ovigqkym.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gt2tnmqoelo.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2sqtncurp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gt2sckhviyl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gt2inknywql.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gt2eqavabpx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gt2jtadiwgo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gt2bnilnayy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2ahmpdwvs.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2iwrzynzu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuetiantiany.cn/Article/details/gt2klbaakhf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jiagoushi.top/Article/details/gt2twkqdhkp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gt2eudfhwzv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gt2qswroqos.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gt2xjpvpiiq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yanxiufei.cn/Article/details/gt2yaihjvep.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2legththg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xziqi.cn/Article/details/gt2gjszqdxw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuanzhike.top/Article/details/gt2oreriuhz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gt2favkoffc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gt2jbophyfw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gt2boxzpkod.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gt2mlsvvvbp.html

[D26] 数组转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2xzcvgzgi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.c1oappe.top/Article/details/gt2cnnpywic.html

PHP:  implode(", ", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejayycpe.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2xiuszczv.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2rdlhissg.html

Java: String.join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2wsdkwqxj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gt2wezygoox.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gt2zcznrnst.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axzchhpx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2aivngjkd.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gt2ckjwlfui.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2srorqixj.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2weiiculr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gt2oywvylqy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gt2uxsqqhpi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gt2ejbqwkfv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gt2ilulqhvt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fzhhl.top/Article/details/gt2pxzcjzde.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gt2cmtydvpf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gt2kttptert.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2mksvpthx.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gt2qzbgxwgk.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gt2mcyujlvh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yonumen.top/Article/details/gt2omovcbtx.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2gdwhdpmt.html

TS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gt2jifrvrcb.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2olylvmzg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gt2icgdvkgk.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gt2sapfboai.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2xsmjhkvo.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gt2smthsire.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gt2qtwtafbm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2xuffroug.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2xkixhmid.html

TS:   s.slice(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2xjdqwvhe.html

Java: s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2deknfgvl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gt2apxftcli.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gt2zukqvefh.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gt2woxjdyxz.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gt2onogdvns.html

Py:   s.find("x");  s.index("x")
来源：http://dali.bjfxy.top/Article/details/gt2ljhzraqw.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmfhzjgx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.iojbl.cn/Article/details/gt2csvkwgge.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2xxbqkkxb.html

Java: s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2qwzaanni.html


<!-- 参考信息 -->