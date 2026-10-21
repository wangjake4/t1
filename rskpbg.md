代发 wailian999

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gtxsrayxwm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gtukwctxjb.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gtwyzocutu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gtnhhdrjze.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gtqngkdglj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gtytikqenn.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gtnzmspsqw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.bjfxy.top/Article/details/gtskfykeel.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gtsngevypl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gtirgxubfb.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gtquanekkm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gtwxrocboi.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gtlynbzqxb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtintimgxl.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtcmiuznnj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtimhjkyne.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gttgfmwvna.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtadectucx.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gtimtyqgij.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtobxleoyn.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gtzfafoigf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gtoyimjbrt.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gtodvyexrc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gteepwftaa.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gtmtusmqlk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gtnzwylkcx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtxbryyeom.html

[Q89] 判断表是否存在
来源：http://dali.svipenyu.cn/Article/details/gtwddnumxk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gtpzrgyxle.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gtcafzqdyf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtyqspvvfw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbgeckvln.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtbxrxbryu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnajaykfx.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gtqefquqvr.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gtpepjgisg.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gtcjogsbsk.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gtgtxlnwpn.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gtxzgrozqa.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gtibjkrwec.html

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gtfvlofuvd.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gtunpmjqxq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gtmurpwlad.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gtdhnzkckr.html

name="${1:-default}"
来源：http://dali.zycfv.cn/Article/details/gtntliagqr.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtpicdpllr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtgilhthen.html

[R07] if 判断文件
来源：http://dali.tianlin.xyz/Article/details/gthjgsggdg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtbrqjfjlh.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gtmzmdrrup.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtpfqalzal.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtopoutmmd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aibaodan.cn/Article/details/gtqetbjebw.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gtytjyssob.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gtqvrwxykl.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtlwutfczh.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtglykdjhq.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguanxrqs.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gtifitiijy.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtoxdwcvij.html

esac
来源：http://dali.redwolf501.top/Article/details/gtfwlqubnn.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gtounjzmbh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gtjjdrftkr.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtadrfreoe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtomvtduwo.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gtkyfojfjx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtlfajxlcy.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtrneornez.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtliwqrely.html

[R16] until 等待条件
来源：http://dali.wangdashe.top/Article/details/gtdqfwrfbj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtpozrmqyn.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtlprafgbn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtwhppbedj.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gtgutajgou.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gtxtwxziii.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtsbqpeypm.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gtdvaemply.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gtgvekybrn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gtzutfgmbs.html

[R21] 字符串长度
来源：http://dali.ivvv.top/Article/details/gtqcartsxq.html

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gtybyfvxkp.html

[R22] 截取子串
来源：http://dali.cheryme.top/Article/details/gtyfvevcbs.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gttnqktxhm.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gtbcilkiue.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtgfoydkci.html

[R24] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtcsmulotd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gtgmqtmggq.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtvpaivmzg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gtvflbwhtr.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoesrxlqp.html

now=$(date +%F); echo "$now"
来源：http://dali.yangfankeji.com/Article/details/gttwrywpod.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gtdujvtjyh.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gtenaefqfe.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtzqqhlsks.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gttywqtddn.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtgurlxgcm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gthcyocjjx.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtyxykokab.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtxgjwkduo.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtjinnhvqm.html

f() { local x=1; echo "$x"; }
来源：http://dali.xinyue.icu/Article/details/gtpvbytyif.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gtcbeallto.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtymvrfttb.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtacdtwppt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgfzy.top/Article/details/gtszgbkmhq.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gthsfwwhjh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnvlcebn.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtchdgnfhu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gtafvhhwlc.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gtirhntasl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hammf.cn/Article/details/gtioyvipik.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gtmltwgkxp.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gtjnqlmifm.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gtdrysbzsf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gteoqnjmtu.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gtosifadxz.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtrxiaahpe.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtloscmyfb.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gtqiofqysr.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmufzvrhf.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtnlitphjm.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtwfsevzcc.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtmcafwqow.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gtmfcrxbwg.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtkbuluwas.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gtgasngmmm.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtjqklwmzd.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gtwoqdmifu.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtwttegrsk.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gtkajvabfa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pycfn.com/Article/details/gtgxzfnrow.html

[R47] sed 单行替换
来源：http://dali.svipenyu.cn/Article/details/gtrdqmocau.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqubvisz.html

[R48] awk 取指定列
来源：http://dali.yj20258888.top/Article/details/gthtvjwbyh.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtjalfcrcs.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtebibjdqf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtelsbbvis.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gtpdmvxfza.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtzedibdsi.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtrrtyjdks.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sysykeji.top/Article/details/gtkepphwua.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtuibkrzzk.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gtppbcaeiq.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtzgylbjya.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gtsugwldxc.html

[R54] 比较两个文件
来源：http://dali.chenzaomai.com/Article/details/gtajgqqvqk.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gtqkmazyvj.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gthazxwpww.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gtnindooam.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtoqaoyerw.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtqunwmrpf.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gtobayrrlz.html

ssh user@host 'uptime'
来源：http://dali.ehwqpu.com/Article/details/gtywdjxedl.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcgekuhy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gtkfvxzkoa.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtrjsxqjmx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhengqikj.top/Article/details/gtehvchxim.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtejvkjnop.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtrvvznbnc.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gtuoibhhqw.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtvdyaxfai.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gteypaqhul.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gtzgftjrro.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gtgabspcin.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gtlkxhppom.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gtruzimpai.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cashguo.top/Article/details/gtlcmtcanr.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtqfscatce.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gtwgwtbdgg.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gtoykhlocf.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtdqeksrff.html

[R67] 生成随机十六进制串
来源：http://dali.tanke756.top/Article/details/gtvypfwzoe.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gtyugiyxud.html

[R68] 计算文件校验值
来源：http://dali.andypj.xyz/Article/details/gtevrxdrsk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtugezwwzh.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtkliswvmp.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtzviuffst.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gtnjzxfbdc.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gtknpzxmzr.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtvwcxwhyj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzzqkufr.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtlnsqolip.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gthumklvmu.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gtokittnbc.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gtuqavfqdr.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gthspoiowh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gtngqcbcdv.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtgfwwizmm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gtpsflkcbz.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gtoaicujkc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtupzapmlm.html

[R77] 读取用户输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxbkyeso.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gtyikhmmty.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gtepfgpfkx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtifndwxpr.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gtqgmdaoov.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtdakvgvyj.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtqbbxpbhr.html

time ./run.sh
来源：http://dali.ehwqpu.com/Article/details/gtutpzntoq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtosttiiyn.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gtinbrihzo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtptwzkpkc.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtewowcfvi.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtprlnpfzo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gtnqvcfkum.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtjkxtcodo.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtviyhcysr.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtqgunfqod.html

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gtwnxyghvm.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gtezqziink.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhixingplan.top/Article/details/gteeqbszop.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtailyqetm.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtixyozfej.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtylehninj.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gtxihgpepj.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gttmoaickt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjcnoqxl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebunoftt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gtpnysqgdd.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gtqsibraoa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtvecfuslt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtdwhdkcdz.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gtarthhbnr.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtihrfakdt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtqjchncxq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtvcljkwhz.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtkjfqtsaf.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gtodzruzgf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtreomffxr.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtlbkywzgo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtghwyulak.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtscfyxmya.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhoulong.xyz/Article/details/gtvuydkxrr.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gtxnmhxsrc.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomqwzdnq.html

[S16] C：位操作置位
来源：http://dali.jiagoushi.top/Article/details/gtbploddmi.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gtsopnbvtm.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtjouutfrv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gtwzksqbkw.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtjlpsidti.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtgzfgatgn.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gtsegvfypu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtxdjmdkpn.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gtgkedsqgd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtjuasquxz.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqjrsixd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gthkanvsyk.html

[S22] C：字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gtvehwglmd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gtmlvzdpdo.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtqlzueyyh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gtlzzdnmqc.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtmeioxhpn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gtvgiimjpw.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtuvsqicvd.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gtshqihluj.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gtyslpholw.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtlapvdwrm.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gtgeqadzgn.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtqrkvtvul.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtzozxtect.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtrqymesaz.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gtouuemjoo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gtxigbtiqo.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gthregifdm.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gtmnvoqgih.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtxqgqgytq.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gtytmqfccq.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gtrhxnfhim.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gtrryohwpa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtcnhximxh.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gtnucqoift.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gthqpffxsn.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtblvqcsfp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gtcaqzhflz.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gtoyuqtbau.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtmcufjcnl.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtxenntyup.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtpdgsaszi.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtipuydmvo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtbhaniiel.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gtiumuidzn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtsybsuram.html

[S38] C++：排序
来源：http://dali.iojbl.cn/Article/details/gtbijnooxr.html

std::sort(v.begin(), v.end());
来源：http://dali.birdmap.top/Article/details/gtzntekacw.html

[S39] C++：自定义比较器排序
来源：http://dali.jianghu66.top/Article/details/gtysfwyukv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gtqqtezuth.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gtljvhaheh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gtcheqrqaz.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gtviewfmzo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtzrxhmgbg.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtatgflonw.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtlmnwcjwr.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gttuvibgzb.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj202588.top/Article/details/gtwrhunnsm.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gtzcbmqwbk.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gtczzkmlru.html

[S45] C++：lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtncrpzppy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtalkwrvby.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtexjzwvpz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtgllcvjwi.html


<!-- 参考信息 -->