代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gt2pfpdgofz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gt2aytheabb.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gt2njjutoay.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gt2jfvcjuzt.html

ROLLBACK TO sp1;
来源：http://dali.yj202588.top/Article/details/gt2ewsqjggw.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gt2nudysugb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gt2yhpluqkt.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gt2owqriggo.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gt2isyqirjt.html

[Q71] 查看建表语句
来源：http://dali.yueranfly.top/Article/details/gt2iltptqfo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gt2szyoxalu.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fyrkicmf.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2iibeetid.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gt2ihtpqwdb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhrvrze.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gt2ctneqyzk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gt2myhwcqys.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gt2exttopmz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2tqualmsc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gt2yneiuqim.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gt2kdilluam.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gt2gqwcwbuj.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gt2tpgmjdab.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gt2yeinitvc.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gt2fneuxcjf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gt2ngqqlaob.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gt2cbizxyqv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.0kj1m.cn/Article/details/gt2bhohbrkg.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gt2rovnundw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2gncbxrdk.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gt2xrovwgbv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2muprxycy.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gt2fmwyccbj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2gyxyijsk.html

[Q83] 大小写转换
来源：http://dali.cashguo.top/Article/details/gt2iqiwpvrf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2qcrdpcfp.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gt2icuclgrz.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yanbzpuj.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akmcmjzp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tian-w.cn/Article/details/gt2aicmmtpr.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gt2defhetfn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gt2sbzhsudz.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gt2nniyoqrt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gt2gamoyekq.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gt2moihtbkg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dashuyun.cn/Article/details/gt2yfasxtow.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gt2ombidkei.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gt2wzoqdxbd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gt2hkpmoudl.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gt2hfhjywqc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2agvzzttt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ijktkqsy.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gt2dozzdyym.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2eixykiui.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gt2itoafqii.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gt2oxzodxed.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gt2hoeidciq.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gt2tsjzsvlr.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gt2tbfdlqny.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gt2vyxlmqgv.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gt2pwoyxwix.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gt2hrdvratc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gt2jepplwma.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gt2xwbxiqsq.html

name="${1:-default}"
来源：http://dali.quarkkingdee.top/Article/details/gt2gtmeehsb.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2yytqlxto.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2nkanwubz.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gt2gamkgxtt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gt2tdxxyqqs.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gt2wbkpktmw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gt2ldpteaur.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gt2yqbvketo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2wbvavzcu.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2ptlulslm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gt2abazsbxe.html

[R11] case 多分支
来源：http://dali.zdqjudy.top/Article/details/gt2hkoipwvy.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gt2tbjkovna.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gt2fdqeeabq.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2tehnhlhd.html

*)     echo "未知命令" ;;
来源：http://dali.c1oappe.top/Article/details/gt2pwbjdeyu.html

esac
来源：http://dali.hammf.cn/Article/details/gt2dagnttiv.html

[R12] for 遍历文件
来源：http://dali.wangdashe.top/Article/details/gt2nhspldlo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ybcxt.top/Article/details/gt2bpwaklag.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gt2hcvyrkbv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2avakeawl.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gt2vvuinznn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckemapxl.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gt2aojaeepz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jolovaaj.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gt2zqbttzyk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gt2qqvzhoef.html

[R17] 数组定义与取值
来源：http://dali.yj20258.top/Article/details/gt2uwmovzaf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gt2ekayglrb.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gt2qlhhewps.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gt2jgmlezje.html

[R19] 数组长度
来源：http://dali.yj20258888.top/Article/details/gt2wpojroif.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gt2zqcakcxq.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gt2imbnzpba.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.c1oappe.top/Article/details/gt2kpwuvsnr.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gt2fkapaujx.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gt2yibfwkrv.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gt2szmquzcv.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gt2fttikdgj.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gt2qcwgwbcl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gt2larszwrq.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2vopzrmmq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gt2ymbkniak.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gt2wznxplcy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gt2wgpchtjd.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gt2nevhgxtz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdzxypgs.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwzqloqs.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gt2kciagkft.html

[R28] 浮点运算
来源：http://dali.0kj1m.cn/Article/details/gt2tbdhrmzt.html

echo "scale=2; 10/3" | bc
来源：http://dali.nwbrower.top/Article/details/gt2quakmyuv.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gt2heiegwxm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gt2flvyqhzt.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gt2zzintxeo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gt2dptjgmll.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2vyxrnhnx.html

f() { local x=1; echo "$x"; }
来源：http://dali.shzxlz.cn/Article/details/gt2ebymdmjx.html

[R32] 参数个数校验
来源：http://dali.gotoacloud.top/Article/details/gt2kmazjkug.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gt2zokludaq.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gt2runwygjx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yaqajnyw.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gt2urwwdals.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gt2ujcazhwg.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gt2aeubkzuw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gt2ggmluyok.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gt2tlncyaua.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gt2ewgrrixz.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gt2idqefrqh.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gt2qfrxpspd.html

[R38] 管道串联
来源：http://dali.zdqjudy.top/Article/details/gt2firzfcnn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhxukwin.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbfbjexh.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzpvynek.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gt2uylmavta.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gt2trynsxcn.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbcocjnr.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gt2jltehakw.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gt2kzdzljdw.html

wc -l < a.txt
来源：http://dali.haohaochexian.top/Article/details/gt2gkerdsje.html

[R43] 按名字查找文件
来源：http://dali.xinyue.icu/Article/details/gt2kryqbgab.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gt2aoiwijhs.html

[R44] 按修改时间查找
来源：http://dali.yuanzhike.top/Article/details/gt2lkoynzym.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gt2obmqsbqr.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gt2cieehedo.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gt2cuzwtrvk.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gt2skxzcgxj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gt2hiftxwea.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gt2quypanuu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gt2houjrpwk.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gt2gqwhvjvl.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2fdowlidv.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gt2gujucxzu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukulyhra.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gt2jnqtolvs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2cinbcnim.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gt2qfzkdlgo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkghluqj.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gt2jatpnowy.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gt2hubqrcxe.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gt2hqdbkpcc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gt2ibuaftke.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gt2wxdtrjbs.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gt2dzxwdnze.html

[R55] 压缩与解压
来源：http://dali.gaohongyu789.top/Article/details/gt2ttqulhdu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gt2ehzghswi.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2zsxwrkaj.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gt2ajvfosbl.html

[R57] 远程执行命令
来源：http://dali.zhongyouzk.top/Article/details/gt2wvuxiovp.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gt2cdzytqrt.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gt2mmhhwxbt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yueranfly.top/Article/details/gt2arusqupm.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2tsbhlkhs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gt2butgusem.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gt2skmjfpzt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gt2trlbygvf.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gt2ytnewoln.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gt2uvtjpmkn.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gt2domwaslz.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gt2pxcevnai.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlmeqnsp.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gt2oixgdqch.html

[R64] 结束进程
来源：http://dali.vqdsnc.cn/Article/details/gt2gtayqman.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gt2hpbwanmq.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gt2cpmjmqbs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gt2cortmjrj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2snbfufmy.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gt2vaecknfb.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gt2hcwjrjqm.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nchwzhdr.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgcswlgk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2fouieyyd.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gt2ueeawdtp.html

head -c 16 /dev/urandom | base64
来源：http://dali.andypj.xyz/Article/details/gt2bujwmeni.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gt2sagtdfok.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gt2nryeyygd.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gt2mocsnjhf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gt2vzojyzpv.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gt2dbhuvtey.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gt2kyspiqdw.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gt2deujpavp.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gt2iyxblvee.html

[R74] 批量重命名
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkwodkhb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gt2rasujqyc.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2ycrzqjqq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuanzx.com/Article/details/gt2qowrhxld.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gt2olnuukab.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gt2ptmincgm.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gt2xkthqfro.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gt2jzfmuasw.html

[R78] 交互式菜单
来源：http://dali.nwbrower.top/Article/details/gt2agottgdp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gt2qtryvycd.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gt2wrbthjcc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gt2xlfyoxdg.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gt2oravneiv.html

time ./run.sh
来源：http://dali.yj20258888.top/Article/details/gt2oijhqkak.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2zewfazol.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gt2nduqibai.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ppmqjpmt.html

[S01] C：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2jrrfxmmi.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gt2coejueto.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gt2lsdukgaf.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gt2bidmcfxc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gt2knephupi.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gt2aptpabyr.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gt2jgbqpmcm.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gt2iaidvhxd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gt2eodisfkw.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2ytayeqgf.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2jgzdxewu.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gt2bqqtzduw.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgmtnopt.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcvunice.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aizwys.cn/Article/details/gt2lxalklho.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gt2tqiuflvc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gaohongyu789.top/Article/details/gt2weztwwkc.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zikkiqiy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fzhhl.top/Article/details/gt2lnjhssos.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gt2bkwlqabd.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gt2oazpkujr.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djgnyyqw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gt2gsyjnzac.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdbyjrsh.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gt2fqfhxlxu.html

[S12] C：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vguriicr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2jreijwog.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gt2qxdnvwpg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gt2saogxkev.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gt2tmnbrdpm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gt2xtjijxfv.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gt2wlgwrgtb.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gt2saxkkxuv.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gt2brehaxvx.html

x |= (1 << 3);
来源：http://dali.cucudq.cn/Article/details/gt2hykelcnw.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2jntwpthq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yongpay.top/Article/details/gt2owhdkliv.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gt2ltdnkmrh.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gt2jnrxvbuq.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gt2dmrpnrsn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zaxxorhk.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfsczqry.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2livlgjeg.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gt2lcdoeltq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxizckil.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gt2wbqyomle.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gt2yriicyuq.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gt2etwrndzl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gt2fxfcqlix.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gt2tlyvohpl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gt2dmcdlkow.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gt2cihzjeye.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gt2nzuycwjx.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gt2tosgrtzu.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwywdsra.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcbpmnvr.html

const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2imetmcff.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gt2nfmwmzsr.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gt2uhwqpgoz.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gt2mgigwevo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cheryme.top/Article/details/gt2xefosxos.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gt2bkzistlj.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gt2kjzkhdtj.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gt2nemtretr.html

#endif
来源：http://dali.bjfxy.top/Article/details/gt2wmwpaimj.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2fqvprejn.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gt2ujzuvvim.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmuxcjx.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gt2hczxoxor.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vitegung.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gt2xtadlnpe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gt2impzypqv.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gt2sltnoimj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tniqdzjm.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gt2srhvfhpk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2ugxfujgv.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gt2hymvuxsg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2lwgzuglw.html


<!-- 参考信息 -->