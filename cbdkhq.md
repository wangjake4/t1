代发 wailian999

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gt2tgfrmdbr.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gt2fxstturl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gt2srtkplce.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqivylli.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gt2mjflinzd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2uyixrufp.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gt2bquvdahu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gt2jgditctg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gt2ajphdcjw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gt2kbfbmbpf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2odnrfngf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gt2lwtviqap.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gt2fejbafbn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gt2lgyfrzcz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gt2ugixoojj.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gt2nfjqtsxw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gt2uvojjust.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2vorgxscu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2ifrlcovu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2vekkqvxv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2abrphzlc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2lmdszuxj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gt2byyoijgj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2cuxbsurd.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gt2erntnawd.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gt2nihkpdic.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhxqsldk.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2bkybaxtl.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2ftyowxmf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2recsuxoi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gt2idwjfqun.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gt2qaepqkav.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2cxrmzeei.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2dckejlxv.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gt2mfufjbgs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2scbvmzgo.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gt2fzoluhwb.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gt2cyvhunyk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2qrvdopgc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jiagoushi.top/Article/details/gt2rnzndwwo.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gt2vrmmsymh.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gt2jfpyjbyn.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gt2vptyptfs.html

Py:   except ValueError as e:
来源：http://dali.ivvv.top/Article/details/gt2oisxxthn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gt2zrrfjwco.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2sseqflje.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2ktnxexlb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlqtgrit.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gt2pwribszj.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gt2uocoqmga.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsfylsiw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gt2ytogqgwp.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gt2szlthgzg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2mamjkwns.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2psjktkac.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2uhzjhzku.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gt2xkcgjmbe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gt2hleqxwzk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.vqdsnc.cn/Article/details/gt2ndkcufdu.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gt2rxxekrws.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpmwjhkc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gt2hwcympfa.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkfseola.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgwdgzfk.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2pqtazfid.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gt2hxrvtqrv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gt2fakgridi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gt2cyafztqr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlhmlmgb.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gt2lxgzkxov.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aibaodan.cn/Article/details/gt2vdxraxiw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gt2ucwfmney.html

JS:   e.message;  e.stack
来源：http://dali.vqdsnc.cn/Article/details/gt2ntnetsqv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfeybdxe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gt2askobkuu.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gt2egaotrmi.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gt2hxzkytfe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gt2msynawtp.html

[H09] 带错误码的异常
来源：http://dali.9152youxi.cn/Article/details/gt2fxsnjnkj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj202588.top/Article/details/gt2urhntxha.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gt2xwoodemi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkaaahkp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gt2ugxtkhcy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrbitvmf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2xclwbetf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gt2cdjcbdis.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fengsongda.top/Article/details/gt2pccijugd.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gt2gvusyhqn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gt2hcdfybpq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2cfogmzdd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gt2oxjqhnxd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gt2dwfnhfcm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gt2rftgwvlz.html

Go:   defer f.Close()
来源：http://dali.guowangkeji.top/Article/details/gt2gfqnedxh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gt2gtimdgrg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2tbbcmmgv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2cbjjftyw.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gt2onnnscws.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2cehzhhbo.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gt2wiykqvjr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2zqrnetdy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpouwgef.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ctifzzhw.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2ybugltpj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zycfv.cn/Article/details/gt2majvhzax.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gt2kywsnkjv.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2qjhokfjq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gt2uspeginr.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gt2vtmhhnzw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2lgrwkrew.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gt2rrslqmgb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gt2vemewxdw.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gt2plwqukbj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gt2nmnjocur.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gt2qabajpva.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gt2jeaskmmh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2pfyxbcut.html

[I03] 提取捕获分组
来源：http://dali.zhixingplan.top/Article/details/gt2lyhdsltx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuanzhike.top/Article/details/gt2wqmewkhq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gt2wobtsodc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gt2ejpghsqf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hysaishi.cn/Article/details/gt2hnxyvaoq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sxryk.cn/Article/details/gt2nsaqjqad.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhengqikj.top/Article/details/gt2xdxooydu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfeymyss.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivuyxdbp.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gt2cfzxiizq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gt2jbusruvw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2wtzsxdku.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gt2vbesqzkd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2vztxtiqa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2uraewmkd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hnqzz.top/Article/details/gt2dzlgusfr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2wtncmmja.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.fengsongda.top/Article/details/gt2hmsiwcma.html

[I05] 按正则拆分
来源：http://dali.cashguo.top/Article/details/gt2ynpoamda.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258888.top/Article/details/gt2jsgedmbm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sysykeji.top/Article/details/gt2nxadksaa.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tykrfmec.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2mwynllph.html

Java: s.split("\\s*,\\s*")
来源：http://dali.haohaochexian.top/Article/details/gt2ojzwovpi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2gfypxbls.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2kjjysmvh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhoulong.xyz/Article/details/gt2atedvowp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sweek.top/Article/details/gt2ioxmferb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gt2rmftmzsz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gt2ctcgjnur.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuanzx.com/Article/details/gt2bvxadfrs.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrehnql.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2qpqmzdhi.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gzhubu.top/Article/details/gt2fhohacem.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xinyue.icu/Article/details/gt2viwtoopp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gt2fukhzsym.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gt2bugzulac.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gt2yjcgtbtn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2pquxssye.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgayxgab.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gt2fdqwpxlo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yueranfly.top/Article/details/gt2vjsdmtjd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gt2pxhtkcom.html

Ruby: s.scan(/error/i)
来源：http://dali.zhoulong.xyz/Article/details/gt2xlnehegj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gt2qxbukhjz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfnodxam.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gt2ttytoewr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2ljsibzye.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gt2nffkdspu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2wlzqczgx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpgotyye.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gt2dfksdisw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gt2cqnffood.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.iojbl.cn/Article/details/gt2qifqgrip.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyetdzvw.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gt2qzztliwu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2pwjagsok.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2blzbdzye.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gt2seekisoo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gt2sopgjdub.html

JS:   new Date();  Date.now()
来源：http://dali.svipenyu.cn/Article/details/gt2mppzbpsw.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gt2lfolmnjh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gt2trljfggk.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpfbgbjz.html

Ruby: Time.now
来源：http://dali.chenzaomai.com/Article/details/gt2xujzkspj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbhuijwc.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gt2qprvdnxu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gt2zkpesnov.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gt2otsjiwbu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jianghu66.top/Article/details/gt2sqtgasyj.html

TS:   d.toISOString()
来源：http://dali.jiagoushi.top/Article/details/gt2vaeiyvrl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daria6918.cn/Article/details/gt2jchhzclg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gt2gqotvada.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gt2gxzfzmwv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gt2uspsmuyh.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gt2yzvtgzod.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gt2xxsfkdhj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gt2nmsmsxeg.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcgrjvz.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2gduftnxy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2donihqhm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2egagsqna.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2bmwzbnrk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gt2ndyjxvwy.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gt2avpwxura.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gt2szctclmo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2pihyybkg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gt2nhkzlynr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aibaodan.cn/Article/details/gt2nwgtdrbq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pycfn.com/Article/details/gt2ahdwunsi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.iojbl.cn/Article/details/gt2sonysuaz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yuxming.cn/Article/details/gt2dqnjcbtd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uflpvaby.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gt2nsopxljd.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gt2tdeiauci.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gt2rwwqzdja.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gt2nfqopzey.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gt2uteixluw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gt2jeiborfg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jyoumei.cn/Article/details/gt2elofupmt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guowangkeji.top/Article/details/gt2mpmkthca.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xinyue.icu/Article/details/gt2vjmyrifv.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gt2yrhdsnxs.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gt2ddykblwg.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gt2pohfexkz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gt2omulplrp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2malsgjli.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gt2hquiepqw.html

Go:   end.Sub(start).Hours()
来源：http://dali.sysykeji.top/Article/details/gt2sgrbuody.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tian-w.cn/Article/details/gt2tebpsiip.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gt2lapdymtr.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gt2yflnrvsg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2irobjbdr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhongyouzk.top/Article/details/gt2mgxzabuf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gt2tugsvcqv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gt2jgpcnzgf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhongyouzk.top/Article/details/gt2dbcnwhyq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gt2ndmgznsr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2yvaoskqo.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gt2nvjrjtwh.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gt2qofhgbbb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gt2wvchrjdy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gt2ljocefur.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gt2clzmodqf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gt2cyyfdbax.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gt2pknsxuuq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gt2xguxarpr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gt2umujzbhd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gt2hoqpzizl.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gt2bxwrsbby.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hysaishi.cn/Article/details/gt2rxrnvnyg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gt2kbxskozl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2gjnylxql.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2xvjjsaev.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jomzqypo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lplelkvg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gt2jvhdeeke.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2fzccjqjl.html

[J10] 取今天 / 本月第一天
来源：http://dali.0kj1m.cn/Article/details/gt2bnyqzefi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjccoyci.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gt2fvytncwh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gt2ggazfstm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2ptsvnjof.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ivvv.top/Article/details/gt2mxgfyaib.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gt2fkqerjjn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adjwozdn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2eruthxes.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2jlxtnwpy.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gt2tdydbfbd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2lxqqjuwb.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gt2elrpzucx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gt2fopkbzwc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2brtvjazv.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gt2rhgsdelt.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gt2ghcravfe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gt2kezwzcep.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2yhnzghiu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvpzohaa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2rjbmutxd.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2mdqnibxy.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2xwwauwbz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utdipspv.html

JS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2apwwxxfp.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2jvtlzetz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2qdedulkj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gt2fcnhbxqc.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2ebnzlfwg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2igtxseeo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gt2unwsdyjn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gt2fajwpdqn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cedcheqk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2vfjycywl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2qwfzetyb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2emwyomsb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gt2jpbzuodt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gt2tsemxzvx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gt2juvakrts.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gt2kgzqoabd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gt2eabjqxsv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gt2aplsguce.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhtehuqc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gt2nfpqkkos.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2ggwvvwyl.html


<!-- 参考信息 -->