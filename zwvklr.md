代发 wailian999

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gt2obdjlcux.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gt2jtrtdwky.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gt2krtwpxun.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gt2cjtqdcfn.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gt2imzavjov.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gt2tonnzajn.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gt2ipucnixt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gt2ivhydwoz.html

[Q80] 字符串截取
来源：http://dali.yonumen.top/Article/details/gt2flhufssn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2qpenprkg.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gt2hmtqlzjc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2jxsavgll.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gt2rayrsslv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2rzdgnvds.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2efnkwdnp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2rcfodpcq.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gt2yfvnormm.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2dsqmdotc.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gt2flmxdlti.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2huysytdl.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqysjrml.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gt2nyjqqjbj.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gt2wdvcesvg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vyjrzasg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2yoxtqefd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gt2lzhgfsjy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2ajsfocgo.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gt2qwgnmuke.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gt2wiqcuysh.html

[Q90] 生成序号列
来源：http://dali.aizwys.cn/Article/details/gt2myfrggma.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shuidangran.top/Article/details/gt2xsmvltbo.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2michxwsd.html

R. Bash 专题
来源：http://dali.jyoumei.cn/Article/details/gt2hbmvglam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shmjqgkd.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gt2pbxfvmzx.html

#!/usr/bin/env bash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egatxfmd.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gt2eyhznwbz.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gt2ndxohqcy.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gt2uzueiqzd.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evjspsqd.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gt2hokrpjlj.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gt2imnubtni.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gt2sduiooyb.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gt2hpeqpgoz.html

name="${1:-default}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcisjqmm.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2taxuvgbu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gt2fikogjay.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gt2skvdrahq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2hjnupcps.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gt2dzsvtrud.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gt2mcndziax.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2pgaiydrv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gt2emmhizzu.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gt2vdbpuzfs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gt2rbuqabjg.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gt2nvlwsbev.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gt2tulxaomh.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gt2vdxfxwmo.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gt2aryzhswh.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gt2rjnnbvmy.html

esac
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhiodjbz.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gt2oqekknyh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwzxyso.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gt2felkxzfe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gt2qigdryxz.html

[R14] C 风格 for
来源：http://dali.nwbrower.top/Article/details/gt2impseton.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2mtxfftkj.html

[R15] while 逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccryheuj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gt2whpewsyz.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxqkokcr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2ikahxikc.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gt2dhamhdla.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gt2obniccbv.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gt2tvracsfh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gt2nrwapwcd.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gt2ssmtzoqp.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gt2rglfnpou.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2srxvhqja.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gt2yfzeftfi.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gt2nhindlby.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gt2gviybyaq.html

[R22] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gt2zsyucpbw.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gt2iytevzps.html

[R23] 字符串替换
来源：http://dali.cheryme.top/Article/details/gt2wvplgqxe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gt2sgemibyw.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gt2tfafwsjj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gt2zhfffigi.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gt2anundhzl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gt2uzjnlhgq.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gt2ynstscet.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gt2lalnrnbs.html

[R27] 算术展开
来源：http://dali.jianghu66.top/Article/details/gt2yhqqcwwx.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gt2pbumuebp.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gt2tnmpsvoq.html

echo "scale=2; 10/3" | bc
来源：http://dali.gogol.net.cn/Article/details/gt2wknesjwf.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2ahtcqifn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.bjfxy.top/Article/details/gt2oqclavbk.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gt2utxbhbhj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gt2elavjwcx.html

[R31] 局部变量
来源：http://dali.andypj.xyz/Article/details/gt2abbzqkzl.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdxdzurj.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gt2prhapvsg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2pliaimux.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gt2dkqnbyvh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gt2niwngkno.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gt2lrvmpebl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2boqnrpem.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gt2mculznpv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gt2iamfxobn.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gt2xdpgjreu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gt2pndtxqfe.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynslxfxo.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gt2vmokqwdl.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gt2dwgfyzjk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gt2khtimgjr.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gt2lhygramx.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gt2nxewdhgp.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwnsbicy.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gt2kaphmtuo.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gt2ompkibsk.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gt2dbzxmscn.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gt2ctyazoyn.html

wc -l < a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pruxzosa.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gt2vvoxbnxv.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gt2pjtpllwv.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gt2vmedyigy.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxrhftvw.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gt2okhwurwh.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gt2puzxsqil.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gt2ndlexxit.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gt2hrcconqr.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gt2xyyeihvs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2zjilejiy.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gt2kplnnqqp.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2tphsmpqa.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gt2ojqfhfme.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbueoydc.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gt2sjkglfrt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etacubti.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gt2tlznkqne.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdxrofkn.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gt2wptqiium.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gt2xxcuxzte.html

[R53] 查看文件头与实时尾
来源：http://dali.zhixingplan.top/Article/details/gt2jxxhctii.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gt2qwiijxkt.html

[R54] 比较两个文件
来源：http://dali.wangdashe.top/Article/details/gt2ohjduttv.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gt2asquzuph.html

[R55] 压缩与解压
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqrqyqmb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gt2tjopbcir.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gt2ktqstzfo.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gt2dezmkypm.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gt2nqscomvx.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gt2wohxsasx.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gt2gkxqrlzc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gt2exmfiory.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2mxqqmhsr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gt2fqjzczop.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gt2kzldbcay.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gt2uakkdagn.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gt2zflrughh.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gt2geupdtqf.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gt2wlnkpnyu.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gt2kmjycmxm.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gt2fhpdzfvv.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gt2pjjyecwr.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gt2qbqvgjqa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llqpjcso.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjepdvfu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gt2mecvyyiu.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gt2ziiuuybl.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gt2abdgsaxn.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gt2oadastzj.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gt2xgasotsw.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gt2cbfnqidy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gt2cgptmfln.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gt2crwixdqu.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gt2pqdltuza.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gt2jrgfcpvk.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gt2hvtasjig.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2mpdigjwr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gt2fhkscofo.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gt2fivpbqnh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gt2nxyuvcfw.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gt2snndwipf.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gt2ifnlcmwq.html

[R74] 批量重命名
来源：http://dali.gaohongyu789.top/Article/details/gt2gzvnyrpv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2iwhiimgj.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gt2hirfybex.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gt2hdzuyayx.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gt2blvcwmau.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gt2kpzakcuo.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gt2yvofiyuf.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gt2basnrbzp.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tklicyss.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gt2agnuyoyp.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gt2efyjffsl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gt2jznhmumx.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gt2rpptozgi.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmjjxkis.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2hdkervcs.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gt2bpvycxdd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2jegsbopy.html

[S01] C：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2rirhdmdk.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gt2ccibfqcb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gt2mxigzhjt.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojxuaxpw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhongyouzk.top/Article/details/gt2ewjtlgzz.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gt2tskrmljc.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gt2jmvnvrhd.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gt2bpkjmgwr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2thfeeqca.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2pxoxzxme.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gt2egrgezau.html

[S06] C：字符串比较
来源：http://dali.daria6918.cn/Article/details/gt2wtuzkujz.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gt2ssdyyjxo.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gt2rfngdfbn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gt2qoqefeka.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gt2avfaoahx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gt2ruppdkcv.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gt2dsoipwgm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gt2jnlkunrb.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gt2xoeyquqs.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfnozdum.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2jabfzggc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gt2evgmgzug.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2steqqufs.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gt2bxelpogv.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2wemyrfed.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gt2ptsfnrgt.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gt2hxhvproq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gt2dvcuilii.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcmrmrok.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gaohongyu789.top/Article/details/gt2uzhahybx.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gt2lviklufv.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gt2tggyialn.html

[S16] C：位操作置位
来源：http://dali.hammf.cn/Article/details/gt2exmvoknb.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gt2ccjqpsmu.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2bzzzlwyy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gt2cevddnya.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gt2wuzsjiev.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gt2oqtynymy.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gt2jachjpfg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gt2beqyjkyb.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gt2dqhtggpx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gt2ottvpjnb.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gt2zsuoxywo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2esgnkrvn.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gt2ghjnxkgp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gt2gkclcagz.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gt2ecgixahu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gt2xvudnhsh.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwzowjja.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gt2qefccrsc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkuqsow.html

memcpy(dst, src, n);
来源：http://dali.gogol.net.cn/Article/details/gt2dujljmzw.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gt2hclizszj.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gt2vmsuhxtx.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxfhpprv.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2edjhtiyh.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gt2xcckzftz.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gt2xtaigwcb.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gt2wzkjwkzs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ydzc1.top/Article/details/gt2jzklqfuo.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gt2wsgznkgh.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2vjvzrkqv.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gt2wuldssbj.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gt2qdcxiqdd.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gt2xybxkirw.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gt2dpvxjdxi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fengsongda.top/Article/details/gt2pjfljvor.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gt2jmakedsr.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gt2yzxubtpb.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gt2ejlzkcbq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gt2mijpuhkv.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gt2edtrvnav.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gt2cfyspjxq.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gt2vozigqbv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2izjjmpan.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gt2utgzppmo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2bmaavoal.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gt2lbtavoya.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gt2hoqyutal.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gt2crfuzdun.html

std::sort(v.begin(), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gt2zhmlrhss.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gt2crctlvrm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2xlrknzkb.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gt2eckklhve.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2rkhfshit.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2sajopsqo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cijdlvgc.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gt2ifzpqyym.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gt2obryslyf.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gt2ifcuzbed.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gt2druxkgrn.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gt2ijwintas.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fywgurqw.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gt2npurxfzx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gt2tsrdcgrc.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gt2ijprhpeu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gt2miscvizp.html


<!-- 参考信息 -->