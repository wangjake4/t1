代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtuidusave.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gtnevcttlv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gtpmtvkczr.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gtsilwdyat.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cheryme.top/Article/details/gtcudusech.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtxhcvwpue.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtlzormirl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gtkztcpxzw.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtkowdytgr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gtsnefkkmw.html

[Q77] 时间加减
来源：http://dali.zhixingplan.top/Article/details/gtgimhmfrk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtffxppgsd.html

[Q78] 当前时间
来源：http://dali.chenzaomai.com/Article/details/gtyszlisxf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.andypj.xyz/Article/details/gtzhtglapc.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtuatsggyb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtobszroxz.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gtulfprewk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtxhslfjcj.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtnbghpjzd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtreyjdyce.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gtgjallctg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtxanqmjiy.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtfuvvqwrb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtnntxccjc.html

[Q84] 去除首尾空格
来源：http://dali.pycfn.com/Article/details/gtctefjcrx.html

SELECT TRIM(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtizvbbuck.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtkzcwechu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gthcgqgnno.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtdqnwwoyf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gtweavshpc.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gtodalnovu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gtjuisysdy.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtxhtjuicl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gtvvlsdpkq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gttjlqwbdo.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtabpstpvp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtmwvngjuo.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtzkooekaf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuanzx.com/Article/details/gttbpmabld.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthjyhxicd.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gtifkhjgoq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjodhrgjd.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gtphsjmfaq.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtcubkpagy.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gtazaeuaak.html

[R02] 变量赋值与使用
来源：http://dali.tian-w.cn/Article/details/gtuwrvmmnr.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtksqewyup.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gtqtpnanqu.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gtdskrninl.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtudqccoed.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gtikboqxgr.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtedeqnljm.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gtrhtdqxya.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gtpiuynuqi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtgbetkdhe.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gtgmmbxngq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gtenqcvjwb.html

[R08] 数值比较
来源：http://dali.hfpthk.cn/Article/details/gtpakwsfxn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtxcrpkofr.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtftxrsdlt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gtplrexwsr.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtyqkyqmvz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtovzrxqzz.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gtlyyfowar.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gtpispmvce.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gthzmlctcz.html

stop)  echo "停止" ;;
来源：http://dali.yj202588.top/Article/details/gtgxoplmvi.html

*)     echo "未知命令" ;;
来源：http://dali.hnqzz.top/Article/details/gtesebpqbn.html

esac
来源：http://dali.fengsongda.top/Article/details/gtcxdcmpnm.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtzsygzxdk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgufenzy.top/Article/details/gtqinvmomp.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtxxpvyvoi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtqtdnjewf.html

[R14] C 风格 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioueaqiu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtklosfhyt.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gttliytqbb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gtqrsnfkkv.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gtmnajfnwr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtymfwqiom.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gthgivacqa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gtazzmqpet.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtbxtxnwva.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyorujtz.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gthlmtwhaa.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gtjucxmlod.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gtqbzpswcr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtghwuvbyk.html

[R21] 字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtoqaaygvh.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaibpsjw.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtmpghujhv.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gtoxxsptxf.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtujqcqzbt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gtcqxqmoqc.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtqvqdtwqo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gtohkkyiqp.html

[R25] 去后缀 / 去前缀
来源：http://dali.redwolf501.top/Article/details/gtacbbjhlx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gtxaxgbnxp.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtlgngdxxn.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtgmoettxg.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gtndxagzus.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtlfewvsjy.html

[R28] 浮点运算
来源：http://dali.daria6918.cn/Article/details/gtrnnkysks.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gtlvsnhqis.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtdaxsoviq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gtephirgsk.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmadhjbg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gtuutlnjwj.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gtfeuvvxzt.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gthibqlwtb.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gtvgtcrdoo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtfrmznpkg.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gtrndlrtso.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gtgjfwpsvb.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtdcqcyagi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtxtyjxkzb.html

[R35] 后台执行并等待
来源：http://dali.ivvv.top/Article/details/gtknooqbqt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtilvrykkk.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gtruiswznu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gtlnvruwuj.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtirkhsnqa.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gtwpyevshl.html

[R38] 管道串联
来源：http://dali.birdmap.top/Article/details/gtirqpjgjx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cucudq.cn/Article/details/gtysjpsiuo.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtjvofnalt.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtiuhhjnyc.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtinuhkmiy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gtqztsxmko.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gtsnjgcjuv.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkghnbxko.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gtrpslvycd.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtlcxdmffl.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuaeorga.html

find . -name "*.log" -type f
来源：http://dali.snrcjt.cn/Article/details/gtujqwlsbq.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gtigikiggv.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gtgckiobhk.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gtkxcpkwuw.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtkngtekvu.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtfmpevrrr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gtrgiovzxd.html

[R47] sed 单行替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhgpfjog.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ydzc1.top/Article/details/gtdzcbhzkf.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdtbyolb.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtpxmpzecv.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gtvndlxagz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dashuyun.cn/Article/details/gtqjvjbysb.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gtoywgawsj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtiltdydxg.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gtepfnwbye.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gtfodwhogd.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gtndvozrqo.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtcgcwpcne.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gtbmtznfid.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gthmzjfopv.html

[R54] 比较两个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtlswapjge.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gtctnzrmqs.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gtmpzwgwdu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sxryk.cn/Article/details/gtqhckaopk.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtyenebodi.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gtkshfjrtw.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gtaxraaqei.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gtzlqmzhgd.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gthiniarrn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtolkpqqhk.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtvqzrznul.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hfpthk.cn/Article/details/gtrebwtvap.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtkoxnrhkx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtpoamxuvt.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtgfavmazm.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gteacoijda.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtsnmlbtpv.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gtwjgfflru.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gtqkvmbyxd.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gtvytpafcn.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gtdhrwdnze.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dashuyun.cn/Article/details/gtuxhjerrf.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtajzzllno.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gtjmnptxop.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gtzsshyvcm.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gtygcnzbyo.html

[R67] 生成随机十六进制串
来源：http://dali.yanxiufei.cn/Article/details/gtcuzldzkr.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gtxggcvthk.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gtlxvlwuev.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtzdtxyrsy.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gtqkeqitpc.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gtcytwzoos.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gtrfmkztum.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gttzzziedx.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtpphnfean.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gtkhlhylvn.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gtaitikzps.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtsuatpdjm.html

[R73] 分割大日志
来源：http://dali.zhixingplan.top/Article/details/gtxhprodzo.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtuszqfgnq.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gthkaeggxp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guowangkeji.top/Article/details/gtxihififv.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gtmsookbuk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gtxjtqsxkt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gtlulunvli.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmrvdaro.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtdjdumrfz.html

read -rp "请输入: " ans
来源：http://dali.nwbrower.top/Article/details/gtiktmjoft.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gtzowclzut.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cucudq.cn/Article/details/gthcpgfgbv.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gtyjadnlhi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nwbrower.top/Article/details/gtwtuoskjp.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtderhchbj.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtwikywjxb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gteeoucgox.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gtoxrdnszq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxeramrin.html

[S01] C：Hello World
来源：http://dali.jianghu66.top/Article/details/gtwubeusjb.html

#include <stdio.h>
来源：http://dali.fzhhl.top/Article/details/gtnhtvysza.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gtzvwvzdcv.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gthteqtgca.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gtxodqdgtf.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gtfopohvnj.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtcxqcjnqn.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gtlbfptijp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtiubdwepv.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyglynyqq.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtqnsjqvjn.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gtbetwnmop.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gtvbuxayjl.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpuizgnr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gtmxyjmvkj.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtmiutmxrw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtsyibjjcp.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gttgrsgdhm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gtaysqtgfw.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gtdrhirtvh.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gtrlerxfkg.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gtlflsgpqw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtpomocoqc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtruitdexx.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtmsfpgrzz.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gtfevchahu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtiwknkpep.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtrehqyepd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gtjjpneeox.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gtbmnhlkjh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gtzwgaodfn.html

[S15] C：类型转换
来源：http://dali.tian-w.cn/Article/details/gtqyczjses.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gtwvvlpdkt.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gtbhvaqtdq.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtdixerzdw.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtzadzoynz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gtuogfkqjs.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gtqxdqunru.html

int main(int argc, char **argv)
来源：http://dali.yj202588.top/Article/details/gtgirbrwrm.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtydmpmjcb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gthkaucnej.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gtpberpycw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtcrmwiuvo.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtucabtvmw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gtmqxtvykj.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtjroabpxd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtjumbqqzd.html

[S23] C：随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiytegpzh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtpfmuxbqj.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gtoibcbdlc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtrvrzptnc.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gtpnwskgnn.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtxgvxzpxg.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gtkzwxvkwt.html

memset(a, 0, sizeof a);
来源：http://dali.dashuyun.cn/Article/details/gtdrcofbbl.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gtudjdvhcq.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtfwtnmchc.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gtoeklrtpr.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gtynlmqxag.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gtuggkihfc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gtuxqkpboz.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlalnwmy.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakncettp.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gtczikvzit.html

#endif
来源：http://dali.iojbl.cn/Article/details/gttzbjuyrz.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gtpxnnfpha.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gtrstkdzsy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtueqqhhnv.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtbhyjcbki.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaflpbhh.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtmwxxffmc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gtkfjolbdq.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gtdwplkeax.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtcivvbjfi.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gtjmesdwkc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gttwxadorv.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtmpwczhrt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtixakqaav.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtonjgvssw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnzncynx.html

[S38] C++：排序
来源：http://dali.jiagoushi.top/Article/details/gtbyuytzuz.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtunuwmymv.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtwhiwavfr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtzenxtnqc.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtxxknsdde.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jiagoushi.top/Article/details/gtseisbdua.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtuqkyopji.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtcanwxyrf.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtjnokotnz.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gtxkoeedgz.html


<!-- 参考信息 -->