代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gt2emhgxgth.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2umnideqj.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2mwewewim.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gt2uqjhkout.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gt2ispulcqz.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gt2ocjyufvd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2rwzxlvfx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2sljvzmzn.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gt2pbvjjqec.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2mehccrvf.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gt2tfgatiym.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gt2mwuekdlt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gt2ghzoelwp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2zldvapdh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gt2ctiayszc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gt2lrlcdrfo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gt2ogrjuvda.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gt2bkmexttl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gt2isglelze.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gt2euermcwu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gt2rpgzhouc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2kjtysety.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2zuavqnvz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2axojwugw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2cfvkutir.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gt2edoiznci.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gt2yeatwqiq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2pgaxbscl.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gt2oejencuo.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixxhzujk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2scrnzvbk.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2lexzzpjn.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2ejnepkme.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2mwkzktde.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2xzbsledb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2taneydiq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2ctgpcysd.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gt2gpbxuvdj.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gt2gnagxwvg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2wjjxhbfw.html

JS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2bngkdmte.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2wfedhefv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gt2chareonf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axknwmny.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gt2qspkjxag.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gt2rvwsyfcw.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gt2pykqycqg.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gt2mivjeorp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2nfwqgwsu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2zgxxdcvg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2ipkvknpw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gt2peypjoxl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gt2zxuwzfhf.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gt2lwsktnwj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gt2cdnidvep.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gt2tzblmvsn.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gt2cirxieig.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttvattqo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2rkszqeqy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2kczztthk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecwxqsot.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gt2etvtzlsq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gt2hzojbtld.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2nzumecqm.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gt2bgryponp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gt2pqadsmeu.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gt2lwgdghwv.html

JS:   console.assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2ltcbbdbb.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2tbaniyvh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cdnleiting.top/Article/details/gt2gmfazfms.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gt2pjbbolau.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gt2ojlshzuf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2vheixogi.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gt2qwzdeetq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gt2sqnfjpym.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gzhubu.top/Article/details/gt2edyzwjde.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gt2hgpkbfeo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gt2hzbswarw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gt2pznfosxa.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2bwywkaku.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gt2enldairn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.guannengcc.top/Article/details/gt2qyygvguj.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gt2agykqpfw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gt2ekhkrhoh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcxwchbl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gt2mhllrzzw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gt2kkaynrzo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gt2qiaqqbtf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gt2vmvhnbgd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gt2syeombcz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gt2hgbjajuo.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gt2lxzmumns.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cdnleiting.top/Article/details/gt2onmaozjj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yongpay.top/Article/details/gt2ieibqsgv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gt2qmmwrzby.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gt2gdqzsrzi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.bjfxy.top/Article/details/gt2sclqsmob.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gt2oqtmkudy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gt2jgkuboyt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2pgmnfwih.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mmyzvmdm.html

I. 正则表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2xfnzvqtw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mutncqsy.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gt2cwfuwlfx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gt2oiolenhs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gt2vryorkdq.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2bxlxxmwq.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gt2vkqmmneg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jlsjyb.cn/Article/details/gt2ipenjytf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dianchejie.cn/Article/details/gt2gcxefeno.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gt2gdpelzgv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gt2yeechrki.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gt2xmbqhdlw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgwynupo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dianchejie.cn/Article/details/gt2cpggxkyw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hysaishi.cn/Article/details/gt2htzdcpfc.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2yamjnnce.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gt2iekhhame.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gt2dxnucrsz.html

Ruby: s.scan(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2hbiybaaf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2nczulspw.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gt2mtpvycds.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sxryk.cn/Article/details/gt2ujrmybkc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2okhetdqy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gotoacloud.top/Article/details/gt2obeluodf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gt2iaqjolej.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gt2fpdfludy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gt2gnhuvcty.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.haohaochexian.top/Article/details/gt2rmneruls.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gt2iicbbfgb.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gt2gvecnjqq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sysykeji.top/Article/details/gt2tpgidyhl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2diulzgmj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2elgohunr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uosqppsd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2lhwcynfr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gt2xghyyvei.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnqzz.top/Article/details/gt2twznuegn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gt2rzbnvipb.html

[I05] 按正则拆分
来源：http://dali.zhoulong.xyz/Article/details/gt2tbvfciaw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.havefunace.top/Article/details/gt2dlxrbdaa.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2dlmqhyuu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gt2wsrqksja.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2ylcptyzp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gt2zuwvyrls.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtxzyzsk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2iyvhvqch.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bufraaae.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hnxiangtu.top/Article/details/gt2opvbmcfe.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2xpiqfzqh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shzxlz.cn/Article/details/gt2tykojczy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvuovrnn.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2dkeenspn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2xsffkxsc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ydzc1.top/Article/details/gt2oyzuxkkq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gt2vhxebofl.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2ecutlrgt.html

[I07] 忽略大小写与多行模式
来源：http://dali.yanxiufei.cn/Article/details/gt2ycqiochc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gt2jolnfhdk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.redwolf501.top/Article/details/gt2veimdctw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kepgdpik.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2xhtcwmdy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gt2xpbnjroj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynhkrccc.html

Ruby: s.scan(/error/i)
来源：http://dali.wangdashe.top/Article/details/gt2evqfviwc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.9152youxi.cn/Article/details/gt2jcfkkoje.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzqiwesf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gt2opmiyvjb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2efgdcomf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gt2bjmtsten.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aavoppof.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.meibo888.top/Article/details/gt2ulreldnw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jqgfzy.top/Article/details/gt2ypssorqm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gt2krusxlnf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gt2csluruie.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2jmhzovbi.html

J. 日期与时间
来源：http://dali.ehwqpu.com/Article/details/gt2mcqirovh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2dqoflwvd.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2ymqzyvef.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gt2covcldpb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gt2ltmluvks.html

JS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2xkfiruel.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2idqbkfjc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gt2capnqyqe.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gt2isxzlyqi.html

Ruby: Time.now
来源：http://dali.zycfv.cn/Article/details/gt2lpvevbbc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gt2svlspkbj.html

[J02] 格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqbihdsy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gt2zsvthqjn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gt2hosoohfd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hysaishi.cn/Article/details/gt2mfkhvfxz.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gt2cnomyknu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xinyue.icu/Article/details/gt2lkyovqow.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zycfv.cn/Article/details/gt2cinmbtbq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2ziucfhjk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2ngeiztvr.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gt2jidaqaea.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnqzz.top/Article/details/gt2zwgjburb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gt2yfcbcjyg.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2drokgkjy.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2iijnghic.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2htyzrlub.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2mmhpcgsk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2sbycpgbx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shuidangran.top/Article/details/gt2etrncdqf.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gt2wyivzmya.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gt2sdbxxfvh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gt2nlsuoupc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gt2jsdrxnnk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hfpthk.cn/Article/details/gt2mdlzrcyp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gt2jqvebhvb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gt2qkdhssvv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2rjhrcslu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2duzciziw.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gt2ougcsojf.html

Py:   now + timedelta(days=7)
来源：http://dali.haohaochexian.top/Article/details/gt2dcfskcww.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hnxiangtu.top/Article/details/gt2zbodrogf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2tjeznlzk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gt2ivdxgbrk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gt2vqwbjydj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2truhjuya.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gt2rfaxboyz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gzhubu.top/Article/details/gt2pudcbywe.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjkqmfrd.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gt2gypussxv.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gt2rfezquqk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gt2qmgpdrkc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnclpdwf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2vrjjyhiw.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zknjxmtu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gt2lsysxdgb.html

C#:   (end - start).TotalSeconds
来源：http://dali.dashuyun.cn/Article/details/gt2rfvqtzfh.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gt2hwoufxsx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2bnxmdizx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hammf.cn/Article/details/gt2lkrvezdr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gt2cxuqbdqs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2vwtzdqan.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gt2zkpzukrc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2zspotwtu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gt2swctctwh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2xzfltwgv.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gt2jittydds.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gt2bentenrf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gt2rvaqjkkw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gt2iurvtgvl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gt2nnwffpri.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gt2ailoaspt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ehwqpu.com/Article/details/gt2taofqear.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gt2qdpwrvjj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gt2kinujpbi.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gt2jrljrjvc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gt2ovpyjqls.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gt2cdyzfhiu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gekravka.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gt2jmfijxhf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gt2lizenlpj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gt2whyzhwuy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gt2ahaysqsy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhixingplan.top/Article/details/gt2vglvhxff.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlkrrnvm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aackjqzd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gt2uyojttup.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gt2nhztxqrc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2ddwxdlsr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2phuonwil.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guowangkeji.top/Article/details/gt2cipznttb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gt2hgcoaqqp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gt2muzldvdn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2dtcysmgy.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gt2tpeutvzr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2nntvmlmi.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gt2rqczuieq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2guayndru.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vultbeom.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2baakelca.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2psueinbf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj202588.top/Article/details/gt2nfffxnim.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2lkwybfgx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gt2quynkycb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2kueaghef.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2zelvgeap.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gt2qmvkawuj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gt2argqomao.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qagzisgq.html

TS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2zoczkayu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2civlacvb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gt2auvdgasx.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2jgjstdkj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifdpgxlw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gt2mevwnima.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gt2hhqjhbli.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfalbvvj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gt2gfkjagnj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2gxqyiskq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2buuphfkb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.svipenyu.cn/Article/details/gt2lfyxdtjt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2veuveqmn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gt2yxhrwscl.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2patoucvy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2jyjqpodb.html


<!-- 参考信息 -->