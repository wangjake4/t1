代发 wailian999

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gt2lzbpsltr.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xervmtbz.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gt2udqvswgi.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mcgqgbcv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnwiqnap.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2ettnfyad.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fxxluvac.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2hnpcoyvf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2medyykqq.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2cyxebxbm.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gt2anyixwmd.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gt2zhdhrwrz.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gt2pgguxssk.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2cmmkswcv.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2omxdhapd.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmibzsbo.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xllrqxym.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gt2iwoukjtu.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gt2kgfmokji.html

C#:   u is User
来源：http://dali.tanke756.top/Article/details/gt2maibkfus.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gt2uobrykls.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gt2ibqadcrg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyckszos.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gt2ecnxowrx.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gt2oysqjyje.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gt2xwmhtzem.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gt2xdhepykj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gt2ghvuszjg.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gt2xjguyvpd.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2nzewrovx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gt2adswbtsh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gt2xbqavlsz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gt2wyfkrrdt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2sgxrxyil.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzxaxgrm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gt2xvbegfyu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gt2fgsuabhd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhftssfe.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gt2tesqibxi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gt2hivyqynj.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gt2qwwpxksa.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2amslslpa.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gt2yzyordfo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgbgjndb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gt2rgcqjyyp.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gt2zbkocmkb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2reovjkfv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2jcvzpgiy.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2oqhqkslc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnlvevxe.html

[H01] try / catch 基础
来源：http://dali.quarkkingdee.top/Article/details/gt2kgnluncy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbqohnyb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gt2mjqpisdb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gt2lobcxkdo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2pfurqrut.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gt2ecjmxnzn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gt2xlldaxbv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjwaujgh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gt2ltujaqbn.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gt2dshvvcsy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbehrelu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2yiacsqlv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2tpyeaxud.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2obwuwoun.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2eefhdjij.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ivvv.top/Article/details/gt2cfwlmnor.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gt2ygopkkss.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2ojahbjhm.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gt2rhyzsozz.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gt2drxwctik.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gomtmbfn.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2owmbsjcm.html

TS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2cynxfurw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vebeicxm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gt2upnkzazp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gt2exhpmphf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2pdrcdaud.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gt2ztymfrbk.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzgthuur.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2rcbibtth.html

JS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2ldsprcxu.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2errqbdsn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gt2dvnzjfwv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gt2bhqhmyvf.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gt2mbuidrog.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rukjsjch.html

[H05] 捕获特定类型
来源：http://dali.meibo888.top/Article/details/gt2rxpsbdov.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gt2coihhpdp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gt2emumxboa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2wvaoxang.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2phddfsed.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zhbprvgz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gt2jgcvcsyl.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gt2feywndco.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ivvv.top/Article/details/gt2efwqybfd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtvuzkcn.html

Py:   value = d.get("k") or default
来源：http://dali.xylfe.cn/Article/details/gt2rkfokphb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2qbxftrwm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gt2kjkegmgr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tsrfsloy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gt2lenjzice.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gt2xkcixjlu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gt2ocneyfsr.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gt2hkksyoil.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gt2kfmdcmuf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnqtxvwp.html

PHP:  assert($x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2aadieksg.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2gadqgzgn.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2sjugbdpo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2fkcvchau.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gt2jcrfhbwf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gt2qbhconsb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2erkysrke.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxdayoog.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gt2oecvprhc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gt2illkcyww.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gt2gqakjrts.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gt2wwhpkemj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gt2zmtakctz.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gt2vohvjogv.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gt2uxzcllgz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gt2xkpzbouk.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gt2teurapdy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gt2wbptegbi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmcxtcqe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqbabzux.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxyvgwlm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gt2ddfinkfy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gt2vzsytpeh.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gt2xsumxyrw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gt2okcamcvn.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gt2eemiefmm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gogol.net.cn/Article/details/gt2imqwenzu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gt2kwxeslwc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2moektnxg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2yqytpcqq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgufenzy.top/Article/details/gt2ocwrzzak.html

Go:   defer f.Close()
来源：http://dali.jinqigufen.top/Article/details/gt2bibzajfe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gt2hxybefay.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2atnppftl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2fgbcwiqa.html

I. 正则表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2kgwestju.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2eyeomjhq.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gt2qygavrcs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2umctdphx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2onnyxlwn.html

JS:   /\d+/.test(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwovocys.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2auevdsgy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gt2yuplblxz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bitimlfx.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2ekfhvcda.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrjjhoul.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gt2bgebzivq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2rbqvzmux.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gt2aerejzzt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqeltgwv.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gt2lcjenrkc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gt2ijvzklah.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xziqi.cn/Article/details/gt2gpsmbggv.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gt2chqjuyrm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258.top/Article/details/gt2pwfjizlq.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gt2nnoiiojc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvorfnsw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uobqzmhu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gt2lvjsimag.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqvvpwaj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gt2jyhbufuz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sxryk.cn/Article/details/gt2vwwfgric.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gt2pzcpcxwk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cqqwz.cn/Article/details/gt2jwzchxhc.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yulmnerw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecndpazo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2kksbtcfw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2dchefleh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gt2ehvuznow.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2urzcatdg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zycfv.cn/Article/details/gt2kqdqddoa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hysaishi.cn/Article/details/gt2oodphkyg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cheryme.top/Article/details/gt2gxmgiyva.html

[I05] 按正则拆分
来源：http://dali.smart0.xyz/Article/details/gt2awfptfbg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2jmklhgoi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2hxiiyuln.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gt2vmzinxwk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2paihddve.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gt2sxizzhxo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2ncanyhqw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gt2ghtbgele.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sysykeji.top/Article/details/gt2bivwzrxz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gt2hzlprcws.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gt2lynrfjsd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gt2ootygvqb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gt2xekierhj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2objcwxus.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gt2papybdxw.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258.top/Article/details/gt2fmgwnrhl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhojqjoe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2jtqttvza.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2octkcfjy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gt2hmhpycpl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gt2raksxbmc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gt2zqwowmdb.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gt2ugeywlrf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gt2uywawoys.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gt2ppncecet.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gt2dicsjwxu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gt2wxewahzx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2msutrscb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zdqjudy.top/Article/details/gt2cllznrqh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gt2pzcougwh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2rodtpodq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jyoumei.cn/Article/details/gt2zcksjseo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rulagywl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnqzz.top/Article/details/gt2oeavraje.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xinyue.icu/Article/details/gt2udktefnp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gt2xklypzox.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2wxujppqu.html

J. 日期与时间
来源：http://dali.iojbl.cn/Article/details/gt2aogjhgrw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vpwkwfpb.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gt2lfixdxvw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dashuyun.cn/Article/details/gt2rsqkmzsp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2spbmnotr.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gt2fvwqwcst.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gt2djbxbxkg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.svipenyu.cn/Article/details/gt2vpiptoup.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gt2zadwojhc.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gt2wyjwlrra.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aizwys.cn/Article/details/gt2bwvfqpha.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gt2hngdqbbw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gt2hlnjbysu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2wzgkfsub.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jiagoushi.top/Article/details/gt2ztnjodma.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gt2zigspdeq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gt2assuubtn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmemiaia.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhtdmqtf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aibaodan.cn/Article/details/gt2zptupdjf.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gt2mlrjijtw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gt2mqnjgsib.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gt2gllzeqem.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uanbgxli.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gt2avwnzsfq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2jnvnvvuw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2fmaykozk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2chkpiquy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jqgfzy.top/Article/details/gt2stimzbua.html

[J04] 时间戳与日期互转
来源：http://dali.jyoumei.cn/Article/details/gt2flssbfvk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gt2izqgbvxx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258.top/Article/details/gt2hmtsnado.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grixmgwn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gt2rndujspy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2yvogvrii.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gt2yngykcot.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gt2hohlkbic.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2ilnerqig.html

[J05] 时间加减（加 7 天）
来源：http://dali.sxryk.cn/Article/details/gt2phxqsoeu.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gt2quusrcol.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gt2bbpgnxwy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gt2xzjmmfme.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2vrbsjdxq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2seuctqtj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gt2xnvhdarl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gt2dvbhebbc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2worjvvof.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gt2fgrnhzct.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gt2cvhkkxsw.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gt2jeqfmqwe.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ybcxt.top/Article/details/gt2bpcgsacf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daria6918.cn/Article/details/gt2hckoodwy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangshuangyany.cn/Article/details/gt2limbmewh.html

Go:   end.Sub(start).Hours()
来源：http://dali.aibaodan.cn/Article/details/gt2iisgwjke.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvafyszw.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgfzy.top/Article/details/gt2panlilyx.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gt2ollxigfw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gt2jyvprrtc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gt2linrozpt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gt2wsqmxxfg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gt2talkgxrv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gt2jwjfodik.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdencgl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gt2vsenrvej.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgaiiwaj.html

[J08] 提取年月日与星期
来源：http://dali.yangfankeji.com/Article/details/gt2fartbvnc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnxiangtu.top/Article/details/gt2mpaqnoqb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alnkzfew.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gt2xbdnvuhh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gt2ifvkfgwb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2fjjjkupx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shzxlz.cn/Article/details/gt2wdcunjla.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gt2wifyeycw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gt2wkqhixix.html

[J09] 时区处理
来源：http://dali.cdnleiting.top/Article/details/gt2pkatfqip.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gt2qcropmpe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gt2euocxvoo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gt2lnhdyqkz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2wttugwxi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gt2ryckgwxx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xziqi.cn/Article/details/gt2lppfxfpe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ionkwmjf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gt2kkgjmwlx.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gt2ruciezyp.html


<!-- 参考信息 -->