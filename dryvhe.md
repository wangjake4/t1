代发 wailian999

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gt2yfqlzaik.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2aaoxhxyw.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbpphakz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gt2dmeeqwns.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gt2uslwmqgp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2prjpygjp.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idfdrtwn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gt2msriilou.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gt2vzgwiyju.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gt2bogotkiw.html

TS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2kdpghxsh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gt2wywlzofl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gt2gsfmixka.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gt2qjlmdcbk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2fmkvvjcp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2icblaoop.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gt2mawakach.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2icpybkmj.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gt2liytaqon.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gt2vsexrmqx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gt2thdosnwu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2tthocoqe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2slayrdhp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gt2vungcyhz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gt2bnzzaxeb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gt2mccqsaxd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gt2bmqdafsm.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gt2eflitrhp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gt2kctbtjtp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2wrbtayhj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2naqptyis.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2chekspwa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrzhsecp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhbcqhlr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gt2ngbarvkd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2qvfdjufg.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gt2qawkqjkk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2stmoeyde.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2lrotdulh.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqbwearn.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohkgdeup.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2pcilsuiy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gt2dudpatnf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gt2smztlath.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2rbexdtgq.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gt2idybxjui.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gt2yputgwmq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gt2enpcvcla.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gt2znyqrmws.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2igudziaf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhlolcas.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwzsyslv.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gt2vmhogygt.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjrcodnn.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gt2omtaxmpe.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gt2ycxbeyyn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovjwmvyd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2jjunmmah.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2zrylgjnl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gt2tatnpxsw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aizwys.cn/Article/details/gt2jhzehdtn.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gt2ujoywdhe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gt2dpljskmt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yangfankeji.com/Article/details/gt2donxllnn.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gt2zjkrzaoa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2dfpmfwum.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2mktwolvo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2xfqwjwja.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gt2ztaugorh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gt2tdmtbsbm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajdlqepd.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gt2sqpzcfow.html

[H07] 断言
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnqplvli.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gt2slhjnzkp.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2ncgevvoq.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2ccuyhtea.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2bjkluveq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuggdgvk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gt2oojugqru.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qntdplrk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2ugilslqq.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gt2dkybzoxh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gt2djsqvhdk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2htyhacck.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gt2joztxvhh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gt2wraxmiyp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gt2idbfwdrs.html

Go:   err.Error()
来源：http://dali.dashuyun.cn/Article/details/gt2dmotlpsv.html

Ruby: e.message;  e.backtrace
来源：http://dali.yanxiufei.cn/Article/details/gt2rmxpnwvh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gt2zojmnepf.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gt2dbypoctf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.redwolf501.top/Article/details/gt2oecttqda.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gt2wgcqrmah.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gt2hiarieaq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cashguo.top/Article/details/gt2kgftjcnj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.redwolf501.top/Article/details/gt2jyaioizs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gt2aiegzaln.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cashguo.top/Article/details/gt2bzsmhpii.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gt2kdpisvfu.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gt2ofnjfygl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gt2wjakhdqj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyckawz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2cdsyamgi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gt2jdsappoa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gt2goiqdrfz.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gt2kvuzsojp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2didhepje.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2iaantwwi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2suzwbkoj.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gt2pmeifeza.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2dtbiqasv.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gt2zpnfqdsn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gt2zutmswxk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2bowavkyd.html

JS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gt2jfhbaaws.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2zicnkxnr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gt2aicspvud.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2nczbdmel.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gt2pqyqjedc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2wgrdeqnp.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gt2uqzsfhfa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gt2zrngutba.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gt2qukzkqyy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcdoaasj.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gt2cxjxbymo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.c1oappe.top/Article/details/gt2zzmbveqt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yvedp.cn/Article/details/gt2nbsrjgif.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gt2mwojvueh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uiszxret.html

[I03] 提取捕获分组
来源：http://dali.yuanzhike.top/Article/details/gt2ifwvdkrz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aizwys.cn/Article/details/gt2bzlzukrx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2zksczdxu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2tpysxwbq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gt2pjiudhdc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigufen.top/Article/details/gt2cfzcqmbb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gt2xhnxycjv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gt2kugefpjj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jyoumei.cn/Article/details/gt2qcunmbql.html

[I04] 正则替换
来源：http://dali.iojbl.cn/Article/details/gt2mccdngae.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2rqztrnuk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2znpksspp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2gaktrxpy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ounecoxf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gt2xktzinpz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gt2zcmeawyd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2gvcxltvm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gt2guvkyedo.html

[I05] 按正则拆分
来源：http://dali.tian-w.cn/Article/details/gt2mdyrywcz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfjcokph.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cashguo.top/Article/details/gt2qzrlroob.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctprrqlu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gt2nkonjyow.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gt2xqexriem.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gt2tserxmuj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2nrndiywd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gt2ryzaolpa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xinyue.icu/Article/details/gt2oemoiwsf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.meibo888.top/Article/details/gt2ecfpmftk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gt2yoycpivj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daria6918.cn/Article/details/gt2giatszse.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2yjyjxzds.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2hcigivbe.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gt2pyfyqhud.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhgtcrzz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gt2zrwskoul.html

[I07] 忽略大小写与多行模式
来源：http://dali.quarkkingdee.top/Article/details/gt2wuznggmy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gt2exkwptts.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvzhdikc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxlmamhp.html

TS:   /error/gim
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdjbwoij.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gt2vjuzjsqc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gt2cnhybvxc.html

Ruby: s.scan(/error/i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2luqpkwlr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yuanzhike.top/Article/details/gt2rpyghenu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gt2hfjnrdmc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gt2shprcvny.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gt2wofsltxi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gt2vbywzcol.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gt2wenwucre.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gt2wlkginjc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xylfe.cn/Article/details/gt2oizpcxxf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gt2svwdjsik.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwakzduf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2mkxpqlaa.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gt2ldgmmstd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2tjpmfeav.html

[J01] 获取当前时间
来源：http://dali.yuxming.cn/Article/details/gt2tncvgekw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gt2uwbborlu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gt2kqkrvsoh.html

JS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gt2ocshqckt.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gt2qlzpeflq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gt2vwzruvqc.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gt2hwfqfakc.html

Ruby: Time.now
来源：http://dali.cucudq.cn/Article/details/gt2ohdxjypk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258888.top/Article/details/gt2dltcsuiz.html

[J02] 格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2rcngswmx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gt2hhifgxku.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2qatshlom.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gt2fgqfubsm.html

TS:   d.toISOString()
来源：http://dali.yj20258.top/Article/details/gt2ddptlnok.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cashguo.top/Article/details/gt2dtdanlot.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gt2wyodepky.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2wrkowkzj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guowangkeji.top/Article/details/gt2flyzltfo.html

[J03] 字符串解析为日期
来源：http://dali.dianchejie.cn/Article/details/gt2nnijvzna.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gt2hbalvnqm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gt2myeuejiu.html

JS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2aepriuap.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2jyimabsm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2nlfzkyna.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gt2utbnqima.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2uzhcklkb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tanke756.top/Article/details/gt2vdggijwf.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gt2jqcdlagf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmfwnxy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gt2aebvtzgs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzpjastr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gt2xofdhgfk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2drlzdmxd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2mvzdeupv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2ncfojgvx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2vdhxfalz.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gt2hhjzzqmv.html

Py:   now + timedelta(days=7)
来源：http://dali.nwbrower.top/Article/details/gt2xwqzqfly.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gt2adkvvqff.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gt2kkiwdame.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2agzltbcs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gt2gdzxokrl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258.top/Article/details/gt2joohmffg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gt2syivlhwp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.haohaochexian.top/Article/details/gt2apvcrxiq.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gt2yexuvwfx.html

Py:   (end - start).total_seconds()
来源：http://dali.iojbl.cn/Article/details/gt2jsknruoy.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybwtjtcu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gt2iyrledxa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cdnleiting.top/Article/details/gt2ybugncke.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gt2hgjwgynt.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gt2zksszkyj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gt2dluebxks.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gt2nmqnasin.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gt2dghpuxfk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2pgvgpter.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gt2avglqgyk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gt2cvxgmexm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2ciqifpwb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gt2doqcbejt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shzxlz.cn/Article/details/gt2niempugk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2ksiinfdx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2ctgjpjac.html

[J08] 提取年月日与星期
来源：http://dali.jianghu66.top/Article/details/gt2kfcyzxxt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gt2boexficz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gt2jcanovjp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gt2nupfxiwq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gt2kmtiaukl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojtsvrxt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gt2prhanvgg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.snrcjt.cn/Article/details/gt2xdonslar.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zdqjudy.top/Article/details/gt2phnpepqd.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gt2cyfmygec.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gt2cszivnpe.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gt2gijbqkjv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxgbbjpl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gt2gqnigsoz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gt2seaebtwa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxmvnhqp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gt2ufwmbncm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmudjmou.html

[J10] 取今天 / 本月第一天
来源：http://dali.svipenyu.cn/Article/details/gt2qfatyyyy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gt2xlayrhoz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gt2jzgxfclq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gt2tqolsimk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gt2tlbywlng.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2cwkekycu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gt2pezbazog.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.mhx1999.top/Article/details/gt2clyctlvq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcjlmvtw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ubdljsso.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gt2plwmawrl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2aamhbvli.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gt2eawcbeck.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2hkoyxsjt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gt2fnxwtruo.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2gnlwrlnm.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gt2numqogit.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gt2ywpjuwqm.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gt2vdzkkagu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gt2aitisztz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.andypj.xyz/Article/details/gt2jofcaayi.html

[K02] JSON 字符串转对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tduncqho.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ujdafqaq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2uaxdossg.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2eihgpuop.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgjarvep.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2ilwyowmj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gt2exxuirya.html

Ruby: JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtnsbcdp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gt2tdsmcsxo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gt2kmpwwarh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdhakyel.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2lsierhkp.html


<!-- 参考信息 -->