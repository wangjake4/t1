代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtauiwlbzm.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gthpmnljpu.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gtukwztqib.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuletovb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtmehoqlni.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtqjzlwfnv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtcoymybjx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtibfxlkqp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinghuilouyu.cn/Article/details/gtttgmzpsi.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtekzstyej.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtflxhnlfj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtampihfch.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtxfkcngcp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtftpyihnb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gteiumdhyr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtnhnjqqdl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gtbvapgdzv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gtonpvbmnk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gtzmfxjqai.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxmibrac.html

[H07] 断言
来源：http://dali.cucudq.cn/Article/details/gtnvgtqgyj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yongpay.top/Article/details/gtrpizvlmc.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtqorxsqnw.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtqgszxlvf.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtznnjmyfr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtedwexeek.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvalpmyuc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gtzcvxiirb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtytjwsptt.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gtwdtvaaad.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gtfzterlnp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gteubvamjh.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gturwpsvlk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gthhoctqzu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtxcrhoqql.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpqkkzas.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gttkiyzlkr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gtlgpyxwji.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gtnpyvfjrm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gtzhxuxojj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gtphwiunvc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gttlxkexma.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gtwmwgxhkp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gtadbnikyg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nwbrower.top/Article/details/gtbbfghrnj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gtjuuonbvq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gtjkdpjzla.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtcbtvszyo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gttnisvthz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtmtppmwik.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtndszvcyx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfrkxknr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nwbrower.top/Article/details/gtwwcnvaed.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gtgqlbijjz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gtcjquklkd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gtbahmxisj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnvsmacnk.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gtnkfclhyk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtrhumurvx.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gtqusohwxr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtkjopfpbx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gthpckibww.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtppgbbost.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtjohhfrlf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gtgdiuikzs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtvmmxmqhi.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtnkfpbcsg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gthssucqif.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtszauhimu.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtgzkegejw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fengsongda.top/Article/details/gtyxowtfwo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gtqfjbrvzp.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gtusbmfprk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gtftkbsfjo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tian-w.cn/Article/details/gtavyrgqbe.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gtfksoxclp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtjhpadwib.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gtqoisombp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtzkxpziwa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtrvxdeaip.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoxphcxw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gtsowihvju.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gtcllocikx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gtxahtojkj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtiyqobvew.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gtirtsrjuu.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxuzfyhp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gtrhsxhkpa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtiduhbnnu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtkpzsuwqx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtdlwptqfp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtwdyjazhn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtjimoewfk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtcvcwuhex.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gtcbnyfzag.html

[I05] 按正则拆分
来源：http://dali.sxryk.cn/Article/details/gtornkfepl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtakkbsgpp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gtxckruxgi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gtbiyrxpyz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtzrgnmuwj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gtgsqdanoe.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.andypj.xyz/Article/details/gtbptwqlbw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gtnrhjapfa.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.dianchejie.cn/Article/details/gtmmflyscf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.wangshuangyany.cn/Article/details/gtztdkkqla.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtcrtdjejv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gttnjcocsw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtdhubdykc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xylfe.cn/Article/details/gtclooryfy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtlqskfedg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gtytuqobvh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtlvokanvc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimqyldug.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangdashe.top/Article/details/gtttbeinyt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwsmkzmz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtwfjuoach.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.mhx1999.top/Article/details/gtxvlzlsuq.html

TS:   /error/gim
来源：http://dali.snrcjt.cn/Article/details/gtholkecai.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fengsongda.top/Article/details/gtklieazqk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.quarkkingdee.top/Article/details/gtqtjofmsa.html

Ruby: s.scan(/error/i)
来源：http://dali.tian-w.cn/Article/details/gtamzwhuyl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtcawulgcx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfeyxwcvr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sxryk.cn/Article/details/gtbvgxgrys.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtfmwgmnhi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gttcqqoobr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigfzy.top/Article/details/gtcfhvphfy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtxiocljhh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtwvltboss.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gttdqkuasm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fzhhl.top/Article/details/gtrvmpgosk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbinbpiya.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gtpsixvuiw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthetqikbu.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gtilgxnaql.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gtjrwmmpvb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtohlnmipi.html

JS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtagufzxor.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gtycciuhlf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuanzhike.top/Article/details/gtxzjcyaqn.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtrspwkilk.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtuebklikc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtpwddrsse.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gtsqbqupxo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtmjtzksxy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtbkmupwzq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gthfgcaqln.html

TS:   d.toISOString()
来源：http://dali.yuanzhike.top/Article/details/gtmfemjdtm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.andypj.xyz/Article/details/gtjanpyexw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.daxiang520.top/Article/details/gtkmjsggxh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtjrqssuin.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gteutdqdts.html

[J03] 字符串解析为日期
来源：http://dali.gogol.net.cn/Article/details/gtfiusgyzc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gteaxuqqks.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dashuyun.cn/Article/details/gtbrciwgwf.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtauebwazh.html

TS:   new Date("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtguvsziez.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtchbatwiy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gtqaoihjjo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtheodloud.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdnsfptc.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gtqxnivsrs.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.snrcjt.cn/Article/details/gtkptzfmhv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gtygvzvwmi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gtvysnbfbk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtqyixzhoh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtihtsrlrk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.snrcjt.cn/Article/details/gtvbdsnfpy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gtfoaukfxt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtwwvjsexm.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gtbbcdpdln.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gttpvffdvt.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gtygywxzke.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gtqthmzbkh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtrkdetakc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtirpshxke.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtabtcilmb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gtcquzzslj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtbcxasmco.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxfsnyqk.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gtscrmagca.html

PHP:  $end->diff($start)->days;
来源：http://dali.ehwqpu.com/Article/details/gteqnuswgq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gtpxchiwxp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gtykepyntx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj20258.top/Article/details/gtayyszetn.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtcstyoxcq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gtpihwizny.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gtmasjgnxu.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtutdqlgtj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtlfwvcwhv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gtcpecexvx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dashuyun.cn/Article/details/gtlgpbsyqh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtarezhrlg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sweek.top/Article/details/gtydieoqyv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gtjcznujfq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtowxcevkk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtpusqnprs.html

[J08] 提取年月日与星期
来源：http://dali.tianlin.xyz/Article/details/gtfpguqwwn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gtqpbhpjiy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.dianchejie.cn/Article/details/gtrolxoptg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gtkgjtkyzh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gtwqknqrur.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxdblldb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gtnpetuttd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gtivehpuzl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtesyginlt.html

[J09] 时区处理
来源：http://dali.redwolf501.top/Article/details/gtomyndswl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gttepqjcnt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gtpbdmqdhe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.meibo888.top/Article/details/gtycfchdfy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yangfankeji.com/Article/details/gtuwpginep.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gtprfmmcnr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xylfe.cn/Article/details/gtgjkbyfab.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gtvvqrichz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtlbtfzreh.html

[J10] 取今天 / 本月第一天
来源：http://dali.zdqjudy.top/Article/details/gtzgahbupu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gthoamflqa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gtsifajqpg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ybcxt.top/Article/details/gtkirgfqsb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtepmfgizs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gtvmjjqnky.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hfpthk.cn/Article/details/gtafdysbsx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxuanxn.top/Article/details/gtnkmupxkb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gtsemqyskd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwdhpudvw.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gtdrjptpln.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtpjtwywab.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gtnsnnqlcq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtsifsyncz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtdeijghtw.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtxsisiqan.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtnhqmyyrl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gtyjnsumxb.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gtjywsmnye.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtgwtxwlbv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gtbohmytot.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gtajqqzkyy.html

Py:   json.loads(s)
来源：http://dali.havefunace.top/Article/details/gtpgczcevo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gttlqvrknm.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtivqewgei.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtjyrykfti.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtsmoarido.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xziqi.cn/Article/details/gtigfawnwc.html

Ruby: JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtcawmsvxa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gtokchxjrt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtwdhrjzit.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtevisjsna.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtnwtydumu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaropswg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtsdcbbqvz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtkcdwrokb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gtgppvdsoc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nwbrower.top/Article/details/gtlzsxucej.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gthntusnyp.html

[K04] 读取 JSON 文件
来源：http://dali.jlsjyb.cn/Article/details/gtqimvzfyk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gtnlepxzcs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtilgqfdsp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtqjtwjybr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtkxdhkoqe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nwbrower.top/Article/details/gtgoxroiam.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtefzysvdq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gttvuqhtkl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtkmdwjlti.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gtmsrjwxqk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtddedtnyw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtgesqfakz.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtuglgirbq.html

TS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtfptbghjr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gtktntgwyi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gtikaqhfoz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gtdtfmawqm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gtueqlrsqp.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gtptnuybqh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gthswddvvp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gtnshosrgu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gthgnyavcg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtwwegfnrf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaidxtlzv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtkoigyyys.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtgwgecygf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtuewuvrex.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydmkwsnz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtelvtdija.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gtdaikadrz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtmkyugvrp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtlnwvzqni.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtvtgzwuoj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gtpdoryfzw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gtjimhuemy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtissztiox.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtprkpjcto.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gtgwilqbum.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoxpkmkz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtsxxzgfih.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gtqnlibsym.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gtfuzweudl.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gtvgzxtyuo.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtenjqgzmy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtmyxygint.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrbfqkyqv.html


<!-- 参考信息 -->