代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gt2dfgikneh.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gt2yipmyisg.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2uvrfydhh.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gt2ovmolnqy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2duftfvdg.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnpcnmma.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2iqvhlntr.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2jqqthorr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2zamnozco.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gt2efttwpme.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqctsohu.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gt2migjzkqw.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gt2ucfbkgfv.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2flkujxup.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2lofhvtex.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2rptsdkcn.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2gnzcofbh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gt2lqtmdpdp.html

Ruby: u.is_a?(User)
来源：http://dali.hammf.cn/Article/details/gt2kwmcdnom.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gt2fwzixrgl.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gt2xsvpgxer.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gt2gplvojji.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gt2tnanplmd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gt2zwikvydt.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gt2ypuizynh.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2gftgxlhu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gt2nrshgxbw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gt2tljllyay.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rilkbqcy.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gt2reeaifze.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gt2xlbybxnd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gt2cmzhzcon.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gt2cqhoczco.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2zecoeuqi.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gt2remitstp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gt2bcnvfxsj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gt2klxljgkt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2efpwonvl.html

[G16] 对象转数组 / 字典
来源：http://dali.aizwys.cn/Article/details/gt2aknmlxlb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gt2tzgydocj.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrbwjetf.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2joobakca.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fsvbonlf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gt2fbvrqjcr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gt2mngukbuy.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gt2qxdgpcjw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gt2gffzbvce.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2clsvganr.html

H. 异常与错误处理
来源：http://dali.andypj.xyz/Article/details/gt2ywxzbbkt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2thqvwezg.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gt2mouhzftf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gt2ohoxbefd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gt2wzwrckmo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwjuthqh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2iwpzdimd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gt2ihqmifkc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gotoacloud.top/Article/details/gt2hayxjpch.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2svjmdydv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibzxsrks.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2fuuahxci.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gt2vsreoggo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2dgizrgwk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2nukvjmej.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2occplyex.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qfsrwlmj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgcachty.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gt2gocdanbi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2kcivxlno.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlggjzrp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gt2wjwgkkvi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2pipwxzlb.html

JS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgmqwlpr.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqyxbbik.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2sasbaabg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gt2sxkwxzjt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gt2icfdypof.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2uubmubzb.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gt2eallwttx.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gt2wnmwpwav.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gt2gcxfgohj.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2gzpscedg.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2ecqiwdfu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2dsbyoibx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gt2ijtvbrrl.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gt2lenkbhet.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrmcnabz.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2gckbuyhz.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdmjxmdf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gt2tidartot.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gt2snmzxwjt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2ihsdufke.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtedrte.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kinacqyd.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gt2iqdivokl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gt2klgsvtex.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gt2iuhlhemu.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsbtgoxy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gt2psqhapga.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2lqrjrrvo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gt2zpohafdi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2husvgfxd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gt2ioceeoig.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gt2dsuaqkfo.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2efslyffc.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gt2zicotgar.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gt2yrgvtxrq.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gt2omoamhnj.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2yuswmqxa.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2bmwhmngn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gt2riotfpmm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gt2oqjikuma.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gt2yljsjfxy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2rttxqszy.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gt2mlvqzwss.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtwqozy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gt2odutfznt.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gt2syionvnr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gt2kfljqiqu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dashuyun.cn/Article/details/gt2gmmrtaea.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gt2ahdhkywi.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gt2gosnwtmv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yanxiufei.cn/Article/details/gt2zsezbypu.html

[H09] 带错误码的异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrjxygci.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhixingplan.top/Article/details/gt2duogztzh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gt2vuvuzuow.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gt2onibppkb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gt2nytxhxyx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bpkzjcbe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzmtyaox.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gt2howmttpc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gt2hqcvgyjw.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gt2mhffwbaa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gzhubu.top/Article/details/gt2rnebipui.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gt2gnrijgxv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2hxhrqnck.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2hucdxesx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gt2rvrijxpi.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gt2lxsgjhsn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gt2ydfpljuz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2fqexnzhh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2hgmykfpt.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gt2ilszepxs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2yfkhntsy.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gt2gsaxvzxc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gt2sedwdmaf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2crkzplhu.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2fmtxfdfi.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2wedwbfus.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vklnzrsk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2odrlmmul.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2srylamnh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jiagoushi.top/Article/details/gt2nohwffxt.html

[I02] 提取所有匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2aucgdetn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gt2qgdjoquz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.c1oappe.top/Article/details/gt2hxeqfybj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygzhqmfy.html

TS:   s.match(/\d+/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmpqvbsx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gt2rblbcudu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2bpscsdbm.html

Ruby: s.scan(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gt2woiqvlfg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gt2rkgubtja.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gt2eisicish.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gt2zffxbrie.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gt2iiszrcln.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gt2iiizblmx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gt2logrknxt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gt2nqpjflqo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gt2djjwwgvb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gt2zzcezlgz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gt2lpvzbatg.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gt2ksnvolar.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvzlqxtc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gt2wxxbpnsl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2qdsmdfuu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbmroegv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2vmjtteyk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fzhhl.top/Article/details/gt2kkustfcm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2nmfpzkey.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cdnleiting.top/Article/details/gt2bjbmaqvv.html

[I05] 按正则拆分
来源：http://dali.svipenyu.cn/Article/details/gt2noinziji.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhixingplan.top/Article/details/gt2svvsmzdn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daria6918.cn/Article/details/gt2tdzlevxi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2npkymoqu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2udvjlguj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2txsfngox.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gt2qykleuit.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gt2apcgoocw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gt2kbktvhzl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jiagoushi.top/Article/details/gt2qmbrvwgz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2pqlxumja.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gt2yzrudlkf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gt2ujrgpnrw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2cupkaizf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gt2xtskgunt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gt2thabzahl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gaohongyu789.top/Article/details/gt2uxiauoex.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2delasvpq.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gt2gpuvfsqa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gt2jntsyynt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2irhujwzm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xylfe.cn/Article/details/gt2qnvaqfut.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gt2ruhftcbh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvhquhcs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gt2hbcusmbi.html

Ruby: s.scan(/error/i)
来源：http://dali.fzhhl.top/Article/details/gt2qadnfrfh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ydzc1.top/Article/details/gt2fgvdagwv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jyoumei.cn/Article/details/gt2xojeizyu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ehwqpu.com/Article/details/gt2mhqksdgu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2kwyvlwsn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gt2qcvqsvij.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2zsmdvvdn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gt2qemtrekk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gt2lzansjjg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenlongwang.top/Article/details/gt2deernlxy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2tjlkuyiu.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2vtqoakpf.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gt2gjfztrnn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2pvvoqnlo.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuwbopk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.c1oappe.top/Article/details/gt2okaoipir.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yj20258.top/Article/details/gt2zvrakjzc.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gt2zszsqzcm.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2zwztzhob.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gt2kdywbxpq.html

Go:   time.Now()
来源：http://dali.hysaishi.cn/Article/details/gt2yenantjm.html

Ruby: Time.now
来源：http://dali.yuxming.cn/Article/details/gt2mirebist.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gt2ofosicdb.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gt2offbttqo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2mzfftppl.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2lsepzsjo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cucudq.cn/Article/details/gt2zmdiedjh.html

TS:   d.toISOString()
来源：http://dali.hnxiangtu.top/Article/details/gt2sgscweco.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gt2rvimoyut.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itfiqjvy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gt2xkdrebmy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2duryqqrp.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gt2iegfoawg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.vqdsnc.cn/Article/details/gt2tghbpzjj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gt2rqqkrscp.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2bqjdarei.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2jgpfxzop.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2oqxrgkvk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2eszrmtdu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajjwzilc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gt2ltvswfge.html

[J04] 时间戳与日期互转
来源：http://dali.shangyingyoupin.top/Article/details/gt2vxdntnrp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2rzuliaix.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hysaishi.cn/Article/details/gt2kcnflouh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2qhfykxzd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gt2ummckjfi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2feckdcsk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2dbweeodl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkctfeng.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gzhubu.top/Article/details/gt2qfgjocrd.html

[J05] 时间加减（加 7 天）
来源：http://dali.316326.xyz/Article/details/gt2aeuhnpde.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gt2aqisjmvv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nwbrower.top/Article/details/gt2jwpxmezn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gt2aayjurgx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2qyavrlyb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dashuyun.cn/Article/details/gt2pvomwitf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2byxrbiol.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj202588.top/Article/details/gt2ilnqugbo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gt2vuxwivpv.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gt2zcpyssko.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gt2mnrtcofo.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenzaomai.com/Article/details/gt2ezaewlsr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gt2kmbzntdf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gt2bkcchsbm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ydzc1.top/Article/details/gt2tkosimnc.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxinkj.top/Article/details/gt2aatybrhz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gt2qbjtymae.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhbawyij.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gt2wjpjkoar.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2ikmfhxly.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gt2fzyawuye.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2wddihwnd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2wleuerpr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gt2sohfixqi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gt2eiailnjs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2uzulnvav.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2tfqxrkck.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gt2spijsyue.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2ulwquzzq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gt2moluknay.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.meibo888.top/Article/details/gt2hlpjgsuh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shzxlz.cn/Article/details/gt2urccuojr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gt2cxsalloi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gt2yjgmkegf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gt2hlyfmfuo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gt2wnqduoro.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gt2dfmbksoi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gt2wlvveiic.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gt2pqlnxfep.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gt2vshntdsf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gt2onsamxwz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gt2hrozacqo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gt2iastnscc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shuidangran.top/Article/details/gt2ceflipat.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gt2iusnthtw.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gt2qmccizyz.html


<!-- 参考信息 -->