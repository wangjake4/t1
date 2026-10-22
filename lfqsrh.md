代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afcyegoc.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsodivjv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gt2mbsvzpkw.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gt2hdpjwupg.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gt2rdammkmb.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gt2iwiegaob.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gt2frbxsbix.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gt2hgdmfomi.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2svvxvvtw.html

[Q73] 查看表状态
来源：http://dali.ivvv.top/Article/details/gt2mfgylgtl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gt2ifzuabam.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gt2jjcuqemx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gt2huyxbhrk.html

[Q75] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gt2zxjtvavq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2thjnzzfw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gt2agyufjex.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gt2tiqrnbye.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gt2gqssptbu.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gt2qxvzmoyr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gt2jqwpbacl.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aglnmwxs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shzxlz.cn/Article/details/gt2xxyjulze.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gt2admkfzik.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gt2pmryreja.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gt2fgjlnpui.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2uulsrdfl.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gt2kimokihc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2komtaxux.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gt2tuejzsvs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2clxderhq.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gt2sljcymdj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxjrnzaf.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gt2hffzyaaz.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrdipyvv.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mvvwbfpv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gt2ipcutucr.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gt2ncrpipsx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gt2jwidzasu.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gt2kilandbi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gt2bgilfvvn.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gt2cvwjbxpa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gt2cylivavo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2gaxypsip.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2zjmbqvgm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gt2jpkfmlzz.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zeslpcjk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gt2ivagcbqq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2loavhpok.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gt2xmwiodyp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2yvtrfzcv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yslapupm.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gt2nqxqjfae.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gt2nwgnhfix.html

[R02] 变量赋值与使用
来源：http://dali.yongpay.top/Article/details/gt2vsknncpk.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gt2leqdurpj.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gt2mnijywoj.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2mvfwiwgn.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gt2hszdoppd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbowebkj.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gt2nuumuttr.html

name="${1:-default}"
来源：http://dali.fengsongda.top/Article/details/gt2itqwtwlg.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2zdftuuds.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2ujpplawc.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gt2agferucy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gt2ilivatfw.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gt2cdzeyfib.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gt2zjkexnpg.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gt2gqpllnry.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2icetopzw.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gt2zcimswlk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2ciadsrsy.html

[R11] case 多分支
来源：http://dali.yj20258888.top/Article/details/gt2sonomyap.html

case "$1" in
来源：http://dali.cheryme.top/Article/details/gt2ywmddxkb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpucnps.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gt2xvfdzwcu.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2wnjzavqa.html

esac
来源：http://dali.dianchejie.cn/Article/details/gt2rnybiciy.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gt2tsqhljzb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuanzhike.top/Article/details/gt2sareapfy.html

[R13] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gt2rbodqlkf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2zzimjxlf.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gt2ojacyuem.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gt2xzwugzft.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmqvfsib.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2xsbapxzc.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gt2abaoybgg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2euqmcbco.html

[R17] 数组定义与取值
来源：http://dali.wangdashe.top/Article/details/gt2oaeeykci.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2pvvzaohm.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gt2jgatqxxy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhengqikj.top/Article/details/gt2mcruhoek.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gt2qfqdavry.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gt2teqqtweo.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gt2jexilesu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gt2aohngnvf.html

[R21] 字符串长度
来源：http://dali.0kj1m.cn/Article/details/gt2kaqndrtl.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gt2sfahospl.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gt2eduvqkva.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gt2igftaqtw.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gt2ohnxdvaj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2bdmhmuno.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajnwvbtf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gt2gjfgqpol.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gt2opgcyrkt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gt2oehobkrl.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gt2ugmfhbin.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gt2dufmsuyo.html

[R27] 算术展开
来源：http://dali.9152youxi.cn/Article/details/gt2nlpmhahj.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gt2mlefzvwh.html

[R28] 浮点运算
来源：http://dali.wangdashe.top/Article/details/gt2hlhvvhem.html

echo "scale=2; 10/3" | bc
来源：http://dali.birdmap.top/Article/details/gt2kjzafdqv.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpwgmdwg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xylfe.cn/Article/details/gt2ryaltdtv.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gt2eslpnaxj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gt2ehpdyyjm.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gt2epquiday.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gt2uvbfoovd.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gt2zcqsmghs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2lfuvmcin.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gt2xpcyanow.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gt2oxeuclbb.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2xiiydlkd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gt2ttnmezuc.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2wotoncvk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gt2hehjjduy.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gt2klcfjqyc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gt2fqqunkhi.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gt2lqnofquw.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gt2zvfvgcri.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gt2tkaueioq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gt2hqrcoymj.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gt2bqwddwld.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gt2olyktgwt.html

[R40] 追加写日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2tudtfnuf.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnstqvud.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2osibhkys.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gt2ethebzfp.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gt2jluvoiid.html

wc -l < a.txt
来源：http://dali.yj20258888.top/Article/details/gt2axeyjnjr.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gt2cyppvdxm.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gt2hvcrfald.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gt2yxvkyqkf.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gt2asercutz.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gt2imgwdnuw.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gt2dhnqyink.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gt2ccfpwqoh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gt2qvbatlya.html

[R47] sed 单行替换
来源：http://dali.tian-w.cn/Article/details/gt2jmodkezi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gt2ouayizee.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2ducoejys.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258888.top/Article/details/gt2duelupws.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gt2rttajhjj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gt2nejvfqei.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdnmjjfu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2yddmlhne.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gt2nsgdmyax.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2bjczvcob.html

[R52] 统计行数
来源：http://dali.zhongyouzk.top/Article/details/gt2ynlzorfk.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2lnmezgzd.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gt2fpyjconb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gt2fbumpnwk.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gt2cnbudqda.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gt2ubrljvut.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gt2calfktui.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gt2umokooir.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2yqbmprbg.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gt2edkdwokb.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gt2onvuswpr.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkywtmwr.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gt2sjhpeggh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gt2lahtiaee.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2pdgilzjz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gt2uavclmep.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gt2rpvlreed.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gt2tncsqape.html

[R61] 磁盘占用
来源：http://dali.nanxuanxn.top/Article/details/gt2insnkxhc.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gt2wisivnxd.html

[R62] 找最占空间的文件
来源：http://dali.gogol.net.cn/Article/details/gt2hfbrbios.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gt2zkmdlwka.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gt2ddgvmjki.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gt2pqfxlzzo.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gt2wmqwfzri.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gt2eixfpijx.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gt2odbdzzlv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pycfn.com/Article/details/gt2faqwdsar.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gt2nupfwlpi.html

crontab -e;  crontab -l
来源：http://dali.xziqi.cn/Article/details/gt2gpvihugk.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gt2cgxkjrcx.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gt2owvryyks.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gt2tmumruyz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2liylmseb.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gt2cbmhafet.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gt2mlmimrhk.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gt2abtiwcou.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtvcigfr.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2tdmunrmq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gt2zvjqywgw.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gt2nejceqjs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gt2nmzfnqig.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gt2igfaejff.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gt2yxouwilc.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gt2heqcydld.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gt2qmyhlbio.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gt2qgkmbpmk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gt2imqsqoss.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gt2jptpvybf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2cbblbgeq.html

[R77] 读取用户输入
来源：http://dali.meibo888.top/Article/details/gt2wciadhof.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gt2wzmiyjka.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gt2owajnmmd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gt2jfuehwxr.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gt2prdmlhpr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gt2ubruqywj.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gt2oihctkor.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gt2zzdtinns.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ryqmndxm.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gt2ufhzwcow.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2bynwyycu.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gt2sdwzsfzl.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gt2gjyzfwvo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gt2padtnztb.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gt2evykpldr.html

int a = 10; printf("%d\n", a);
来源：http://dali.iojbl.cn/Article/details/gt2yhnrjjex.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gt2dtqvjkvh.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gt2elfetkgb.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gt2iwvkyveo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2exslcdit.html

[S05] C：字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2svdkkcba.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gt2fehhsmyh.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2umcemelp.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gt2oklgramd.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gt2gjoxjafc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gt2ynvzexpg.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blgpbzcu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gt2axtxuhps.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gt2qpwjjdwb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gt2ikiereif.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gt2dckigknh.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gt2lpduznrl.html

[S11] C：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gt2axelvdrd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gt2oyzeofio.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrcimfrm.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2nzmxnoxu.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gt2pycktoag.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gt2jtudengc.html

[S13] C：宏定义
来源：http://dali.nwbrower.top/Article/details/gt2vplllnaw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gt2yxkxsttz.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2fyxarqpe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gt2lmpwfqei.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gt2powlydyp.html

(double) a / b
来源：http://dali.havefunace.top/Article/details/gt2chudlorc.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gt2kejybmvw.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gt2xdqlrvlz.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2slhnqjje.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gt2qmvqbehx.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gt2ynpcivyh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gguaxglx.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gt2akyoteac.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2zlqpgloo.html

[S20] C：二分查找
来源：http://dali.aizwys.cn/Article/details/gt2prfqgpnx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2qlccbrwn.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gt2rtafjkdl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gt2qudmryak.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2pndqqswi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gt2rjlgbjmk.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gt2krjvbnlx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gt2omqgtjet.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gt2cmqzbufe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gt2cmpnidap.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqdqrjjs.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gt2yjkgdqsm.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gt2cywrzodg.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gt2ywhyiqst.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gt2gxmlzbfi.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2tpxicxjb.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gt2nnjfyujl.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gt2asyrtyfi.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gt2pzfydrex.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gt2hhzonapu.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gt2gcpvqeqp.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gt2mygmdfft.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gt2oqzblgyv.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gt2rcqdmabx.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2lqptxynk.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gt2wqzpldzx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gt2jvzfakal.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxdjbmgy.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gt2fciqbhct.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gt2xyvlxbcy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gt2sfvoiqbm.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gt2qacjckxf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zdqjudy.top/Article/details/gt2ohqpgauz.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gt2uhgivkuw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2ckbzbfez.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgmjovwk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rknbnkjf.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gt2gysfmadr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gt2ahigzbxv.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gt2whouuzve.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzdagghq.html


<!-- 参考信息 -->