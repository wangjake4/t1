代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gt2nwrbiwsk.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gt2mnayrjyx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lydnfcdi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gt2diclcxqs.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gt2vlaetgwx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gt2dszruhuc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2axyknmea.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2agpvbyua.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gt2wpjrxijd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gt2lijqyvsk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gt2otfhqzvc.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2biarrkdd.html

[H07] 断言
来源：http://dali.andypj.xyz/Article/details/gt2xelwqxft.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gt2tczwmrop.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2tvdrdxhs.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2eshyiiqv.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2lvtlmbyz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxzkyxde.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gogol.net.cn/Article/details/gt2evlrsbxs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwyjqqcf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxntjqqn.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gt2cxupxvhv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gt2dshssffa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gt2udnbcwje.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gt2sgrhkikf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gt2ijuwtvol.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgfzy.top/Article/details/gt2fniskqpl.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gt2vecakgoo.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gt2yxnlmrpm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gt2psdvqkkl.html

[H09] 带错误码的异常
来源：http://dali.jqgfzy.top/Article/details/gt2iouztsqu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gt2crbdwbgf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gt2pjrymubk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gt2yzjvzgrs.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gt2scbszqws.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tianlin.xyz/Article/details/gt2amyfrxxj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ybcxt.top/Article/details/gt2ypwyixei.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gt2zxgpbzps.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ehwqpu.com/Article/details/gt2twfueexv.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gt2yshrupsc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umhxampv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aibaodan.cn/Article/details/gt2janolrar.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2pnmjrpxh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2djugnxba.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gt2kkxswifb.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gt2gxllqfqc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gt2csyscxci.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flvsuucn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2sieipyrj.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2insrxhel.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2wwhjdvws.html

[I01] 判断是否匹配
来源：http://dali.cdnleiting.top/Article/details/gt2uydhctua.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2eyoemnyf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2yyohanrd.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gt2iiqgmhso.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2xxkrjmrn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gt2olpuxjxm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ovurdwpt.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gt2xeanbdxd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gt2wlrbtlnj.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gt2qpcghgwz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gt2fitldchr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gt2rpttafof.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gt2vqvuvgti.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gt2udjlbsro.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2ichnittp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fengsongda.top/Article/details/gt2ojzdyusj.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2wqnfmdru.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2zhbsbiry.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gt2jpjnbmys.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gt2slckqdke.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2ljhkyhrd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxnqspar.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2oqzbsizd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gt2ebpxeowv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kerntsed.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gt2txacaeds.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gt2qkqrichg.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gt2yatzekbb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gt2hgbxlris.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2meowjvds.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtsvern.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2aztzrdim.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqvnboc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2qkgptzta.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2cqllbgkv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qkaifkrj.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gt2bbbjvynq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srrwfuxj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2zskmnwoe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dskpvtvf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2goklhfgo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehcqtxlj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2rzqjuvur.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gt2hfbqycbf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnqzz.top/Article/details/gt2fpxoaxwl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gt2fhunxuwa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2bxoefqry.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinqigufen.top/Article/details/gt2ztjucokp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gt2xcxcqpri.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2ohulldkd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2edskexym.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gt2wybolqps.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gt2jptexrmm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2xgslpkob.html

[I07] 忽略大小写与多行模式
来源：http://dali.nanxinkj.top/Article/details/gt2ymwbzugf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gt2iehveitp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gt2yanxhlbu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.vqdsnc.cn/Article/details/gt2eiwzayck.html

TS:   /error/gim
来源：http://dali.yvedp.cn/Article/details/gt2egvhzeaa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gt2jxbbyahx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gt2dhpuynrl.html

Ruby: s.scan(/error/i)
来源：http://dali.gotoacloud.top/Article/details/gt2tasringv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gt2rrzsqcyy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhixingplan.top/Article/details/gt2qmyiwfgd.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gt2aukinsxo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2lyujmdde.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2xavyqvfs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gt2doabhpwv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gt2qwfktczk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gt2upjnlqjl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhwyftyk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgufenzy.top/Article/details/gt2iptoguxx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ibggueqf.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gt2qbnfeqqs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2bbgjjrfm.html

[J01] 获取当前时间
来源：http://dali.iojbl.cn/Article/details/gt2kxrctruh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gt2oidurpqe.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gt2okznoglh.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2ihyleydf.html

TS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gt2bcgcwjpf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gt2evnhvbeq.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gt2ixfwcyyy.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gt2qvtezbwh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbynmxmm.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gt2tfuqauhg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2ouawwthp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnxshqhi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gzhubu.top/Article/details/gt2bwflscpf.html

TS:   d.toISOString()
来源：http://dali.yongpay.top/Article/details/gt2uidskzmm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gt2sayaegpb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcmxrifh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2bxbcames.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuanzhike.top/Article/details/gt2wzqmdxwf.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gt2pbhmzloo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ppjwa.cn/Article/details/gt2cawnkwqn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gt2tjhxcbog.html

JS:   new Date("2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gt2dbeyzqld.html

TS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2fphtemmw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqqzgelz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gt2lzeytjmo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2evhvkpka.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gt2mppqfgyb.html

[J04] 时间戳与日期互转
来源：http://dali.tanke756.top/Article/details/gt2adwijemp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gt2xaxymzkn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gt2edqedqtp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ncotilri.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gt2rbtwfdkq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2moqwgfdd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2upffsthr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gt2gcjtkomg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2hzshbxhp.html

[J05] 时间加减（加 7 天）
来源：http://dali.redwolf501.top/Article/details/gt2lepfbdyo.html

Py:   now + timedelta(days=7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2icunckkv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhixingplan.top/Article/details/gt2xehrnroy.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gt2mpohgnyw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2jyleuxof.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gt2emwvrpih.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2pnwxkjrd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yvedp.cn/Article/details/gt2cyctuycf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gt2emwfzjza.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gt2fnpkfoyy.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigfzy.top/Article/details/gt2ylstqhio.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gt2ygflqyex.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gt2vnpommky.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258888.top/Article/details/gt2ldadamzg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gt2xstcptyw.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gt2ksyzgaoh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbnjwlmn.html

C#:   (end - start).TotalSeconds
来源：http://dali.jiagoushi.top/Article/details/gt2bafashqv.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gt2gimdnuug.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2wkjtgnri.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gt2iyzxgoju.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2twzafbiz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2bctkdpoi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqeyrqrc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gt2bvydslsq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxmxzqxf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gt2ugaemsji.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gt2ofjtnzsn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxuanxn.top/Article/details/gt2oueoawbh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gt2vvojysfs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gt2cxvsipxz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.kuanghao11.cn/Article/details/gt2qtwqtosy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gt2kkhacaiq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gt2ifhpkbnt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gt2ujetqquh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aibaodan.cn/Article/details/gt2zhjkbdmg.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvysauic.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gt2diumkrrc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guowangkeji.top/Article/details/gt2qmdcnokj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2bpcmemja.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gt2tueszdtt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gt2zwdlpawa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.haohaochexian.top/Article/details/gt2fdtrcimz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gt2ocjynqby.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gt2ftnbdwgy.html

[J10] 取今天 / 本月第一天
来源：http://dali.redwolf501.top/Article/details/gt2nxbarvsx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gt2bonphhky.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gt2ivkrwams.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2rmfdourr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2muodithm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gt2nakndmlj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gt2csmdsxda.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzhuynas.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daxiang520.top/Article/details/gt2mcstcwpa.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2yuhhvglu.html

K. JSON 与序列化
来源：http://dali.jinqigufen.top/Article/details/gt2pcnarhdi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2vcopdcbq.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gt2lbyqsgjk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gt2yvcpipvl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtmcshcu.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gt2qcagastc.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gt2xzdkdedg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gt2ynklzuer.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2ssaqycfd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gt2lvleirsc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2bgteymqf.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gt2dmuyjdkv.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gt2gbepxepk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gt2aihxyxca.html

JS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2zfaizcsr.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2zcxgibju.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhbuwcfr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gt2ifmbqvph.html

Ruby: JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gt2ezpdoqsw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvncjnzi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gt2emcwutns.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aelrxnln.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gt2kbnlzmql.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eatxhsfh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gt2ouidaikv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2ztdwhcqq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gt2nymkrrmd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yswwtaks.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gt2idukodmh.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gt2icpcpfcl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2mamknyfj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gt2qfkcunwc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gt2tiivnimd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2qfgtqsoa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2jbjqygvk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gt2mbxsdfgk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gt2xfgcfqsl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2azcjyerg.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdpygfqu.html

Py:   copy.deepcopy(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2ftrsffzq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gt2oagyiwiw.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2aoksuszf.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vozpqkyr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gt2xlmqouqa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gt2sozxwuxw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gt2nnuibvwn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gt2frdljohq.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gt2paqikzwn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gt2dusuklsu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gt2xwfnsomb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2mbpzkdyu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gt2zgqpfyru.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gt2tukxucho.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2kgskplsx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2ofxvrhyx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2vutevrog.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjtwlhqy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2jjppipbl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gt2cgadpvqg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gliplaej.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvkpdgny.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2imahtrda.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2rmzfvovh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gt2gmdmdjxj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2aaqyyhdc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gt2xurjzgba.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2bmoctclt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gt2yefusbzs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gt2zztycfyf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2gbugjktz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xziqi.cn/Article/details/gt2cdlwzuet.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikzpesqt.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2ikdbwjzf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2ooxcsdns.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2fgsicqgs.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gt2jyuutqyr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ugcgongt.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gt2vtvynbde.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpautejl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gt2pjqcbqsd.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gt2vprnuqfz.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2lcmbisvn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gt2jusukvoz.html


<!-- 参考信息 -->