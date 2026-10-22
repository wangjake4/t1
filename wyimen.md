代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.redwolf501.top/Article/details/gt2ngqsaeaq.html

[Q69] 查看执行计划
来源：http://dali.quarkkingdee.top/Article/details/gt2jpbnecyx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gt2jlkxazer.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wluuyvhb.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2uenmkmqa.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gt2qjsxibvu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gt2nwnrifpc.html

[Q72] 查看索引
来源：http://dali.yanxiufei.cn/Article/details/gt2rquiofvm.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2lacqtiyp.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gt2gqvchknp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.bjfxy.top/Article/details/gt2rchrkjmy.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gt2hoyutyyu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gt2hlgvprag.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2uwvemffv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2gjfnbzhh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gt2skinkxhh.html

[Q76] 按天统计
来源：http://dali.nwbrower.top/Article/details/gt2btlrrwpq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gt2aqyhwpcv.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftkybfbj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gt2kfuzvnwv.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gt2gvneduwj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gt2hrmqqayh.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gt2xsxndcjy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daxiang520.top/Article/details/gt2akjfckcw.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gt2dfczyslx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2qqracxwg.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2byecuxmp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gt2sbmwpujv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhixingplan.top/Article/details/gt2bdtalnqo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2vozhdark.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2xlkgieaw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2pxcwphos.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gt2fknypbqk.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyjmovwq.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gt2emvslerf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gt2jmacxokq.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gt2umkawmkm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gt2xgbddnki.html

[Q87] JSON 字段做条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jscqfopx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvzikwep.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gt2werrbivu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gt2woyomfqz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ivvv.top/Article/details/gt2hbtfrbcb.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2thrdrlut.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gt2idpxkfwh.html

[Q90] 生成序号列
来源：http://dali.cqqwz.cn/Article/details/gt2onoqqjbe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gt2dwgftxlc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rrlfbucb.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gt2zdxvpsgy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ivtxmizy.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gt2udvzygie.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gt2dywtmrgw.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gt2euraylnj.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gt2bafsrdtm.html

name="Tom"; echo "$name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2veakgbgt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcclhtjk.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gt2ddezmlel.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gt2atbfeovv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gt2gzebuxeg.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gt2lfmocqna.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gt2vkdqpibq.html

[R06] 判断命令是否存在
来源：http://dali.daria6918.cn/Article/details/gt2osykwxmh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gt2mkdehats.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gt2kfrsarez.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gt2xnuackiu.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2pdzmvcxv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2pnienkiu.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezkrqvhv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gt2gixaykgh.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gt2otefskmt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gt2aewnfujw.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gt2ynyzokzw.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gt2uctsvewa.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kedwyauf.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gt2yohlcmhj.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2dhjhvccp.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gt2rpdtuaad.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gt2nqauwhfb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zdqjudy.top/Article/details/gt2qioyuvtq.html

[R13] for 计数循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnlhkkak.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlmfnoxt.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gt2mnqoaafb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gt2wobdvhed.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2gmokzvvh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gt2pddithlr.html

[R16] until 等待条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrtwheku.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gt2skdslyka.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wskfinqr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gt2oqkoxtvz.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gt2oucmojcr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2plmnvfsx.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gt2semmyikr.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gt2gxnyrall.html

[R20] 关联数组（字典）
来源：http://dali.sysykeji.top/Article/details/gt2yhosxiez.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gt2ffdnfomk.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gt2urcixfal.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gt2fttpfnio.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2dxsntqwh.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gt2mvrnjggv.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gt2zsmkxplu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gt2bqvmtvlr.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gt2qhbhdman.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gt2bccmjgjb.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gt2kvqfunyb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.vqdsnc.cn/Article/details/gt2aeuqxcmm.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gt2wlbphezh.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gt2sibbdosm.html

[R27] 算术展开
来源：http://dali.316326.xyz/Article/details/gt2fqyqryjj.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gt2fmdzqmja.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gt2rilkrdyi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gt2zpybtzwj.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2jqkkjvhp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gt2suabgqat.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gt2xilgojxz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gt2fahjgdyb.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gt2bwyxtmgx.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gt2vauospdn.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gt2gmrecehl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gt2cmufjglq.html

[R33] 捕获错误并提示行号
来源：http://dali.9152youxi.cn/Article/details/gt2akpxpvma.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gt2ajvwdevc.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gt2ouypioyc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2himxbjjn.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gt2seitwfdz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gt2asnvgeow.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gt2sarxbolk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gt2mcnphanr.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gt2thvddjgf.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gt2jlccbwgf.html

[R38] 管道串联
来源：http://dali.sysykeji.top/Article/details/gt2obyrbbcm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gt2mthkluln.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gt2dtlclkjy.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gt2zkpvvuuk.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gt2woisrppy.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gt2gntoozvi.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gt2qvosyvfb.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gt2bexvupda.html

[R42] 输入重定向
来源：http://dali.ppjwa.cn/Article/details/gt2ltgigwsp.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gt2ddzkmxtw.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvskquff.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gt2fculvgge.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gt2jlrpjysd.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gt2kvhwpefb.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gt2vrwackth.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gt2ujbwczfo.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gt2ggwwkswj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkseulbu.html

[R47] sed 单行替换
来源：http://dali.dashuyun.cn/Article/details/gt2ddmeueju.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gt2ilpyymsm.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlioomcb.html

awk '{print $1, $3}' a.txt
来源：http://dali.sweek.top/Article/details/gt2scngcqkt.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gt2vexfaetk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cqqwz.cn/Article/details/gt2wmfpjrql.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gt2bvgydvzv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2cddklrjj.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygaacxcg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gt2llyulgjh.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gt2ubvoiatj.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gt2bjrwpixv.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gt2maetsuaz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gt2yjbtklih.html

[R54] 比较两个文件
来源：http://dali.kuanghao11.cn/Article/details/gt2dthyrjkb.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gt2dbkffcwq.html

[R55] 压缩与解压
来源：http://dali.hammf.cn/Article/details/gt2jiyxvnwa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gt2orxkyhpq.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gt2aardxwxv.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gt2pagnnjmu.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gt2jppfzbig.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gt2ykahsvez.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gt2rypvekvq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.vqdsnc.cn/Article/details/gt2quzpzmst.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2zxhqigor.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gt2himdglbv.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2eaomqxqj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gt2dvclvxxq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbqenux.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gt2cntnwdjj.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjuppvhs.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gt2pqnniksa.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gt2fxvajeqt.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gt2rsjqzjef.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gt2oxnypmnf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gt2vamjixyg.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gt2lzjunirl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gt2wwiypout.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijzgnysu.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gt2cktaafsv.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gt2ibfsestd.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gt2buyfgdlg.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gt2bjutvqsg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2nxreqexm.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gt2nqjxpyui.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gt2wtqalvbc.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gt2hexxfwdw.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gt2teceguue.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2gaokwafm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gt2jnlskfrx.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gt2nwhknxni.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gt2knussdfj.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gt2emcusjpy.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gt2gpjzwfvq.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gt2pyxeqvlb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2lehvqcnj.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2qahxxtow.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gt2zojkjshl.html

[R76] 使用临时文件
来源：http://dali.hywenlv.cn/Article/details/gt2bgoclbbu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihsioymf.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgdmjxxs.html

read -rp "请输入: " ans
来源：http://dali.nanxinkj.top/Article/details/gt2xnggotgh.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwnbgimc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gt2ckivdjoe.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gt2bfxgoank.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gt2avfuqizv.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gt2jsgzcjur.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gt2jktjlmng.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2mvmdegfh.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gt2qtozlgxl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2hgyeeufi.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2ontpcevg.html

#include <stdio.h>
来源：http://dali.hfpthk.cn/Article/details/gt2hvhariyw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gt2fdobouxu.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2wsmgpwes.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gt2dselqfsd.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gt2loilukgy.html

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gt2yveliutc.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gt2oeuxkldz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gt2gdpdtthd.html

[S05] C：字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibvdivpi.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gt2fxnjkoxr.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gt2rexiihkw.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gt2lloeyrhd.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gt2ylpajxtm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gt2bjgdxwop.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gt2bxpqjuka.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gt2astmiefp.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gt2brfbnrdd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gt2uakmuphd.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gt2xhxjdkyp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2trurgdbi.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2tzhvoiyk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gt2sptddzpa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gt2hgfzqxyj.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2buucsyiv.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxypyzpn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ratmunla.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gt2qaoslomv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gt2ytvfghny.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gt2htveoyjv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gt2xmxdwwid.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gt2sjlsvcqe.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gt2xsohxrei.html

[S16] C：位操作置位
来源：http://dali.yuxming.cn/Article/details/gt2rllagciz.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2rialfjth.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2jzdxyuep.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zdqjudy.top/Article/details/gt2kbikipgb.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gt2fwozmhol.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gt2cddpsxch.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gt2gbooytha.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2deougvin.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gt2yjjfodot.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2mtrwtmyz.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gt2hyecbpqi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gt2wmbxxgya.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gt2gatjhyto.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gt2mcdbrfwm.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdtlkags.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gt2ifmutgll.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gt2iphqwssh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gt2woskegws.html

[S25] C：内存拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyrxmofx.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gt2jleucxqc.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gt2rswkcgtv.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gt2qlrsryvz.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gt2thysdlaq.html

const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkbpusvv.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gt2pdbbxqyt.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gt2lfyymsyd.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gt2gsknmnjg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvcqrdgp.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gt2wlbngdve.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gt2bnrrhori.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gt2uwmsbngj.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gt2gwjqgxmw.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gt2ophdwbcf.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gt2iunkdlmj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gt2fnzxkvos.html

[S32] C++：字符串
来源：http://dali.nanxinkj.top/Article/details/gt2pbyofnyo.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gt2yonmvhqy.html

[S33] C++：vector 增删
来源：http://dali.fengsongda.top/Article/details/gt2rkpffzrr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gt2nvjvisgy.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gt2lzbwcggj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gt2vfhmnxaa.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gt2ilxwfmab.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2mfsiqqin.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gt2liwnpfnz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2raqmxtpo.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gt2hwwjwunv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gt2ogsreiwt.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gt2cbsesufo.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gt2edwglfgu.html


<!-- 参考信息 -->