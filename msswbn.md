代发 wailian999

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gtnmfnfgow.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtvxspklct.html

[Q81] 字符串替换
来源：http://dali.cheryme.top/Article/details/gtqyqzoxyb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtqdejhkff.html

[Q82] 字符长度与字节长度
来源：http://dali.aizwys.cn/Article/details/gtdspmnxab.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtbmyqdqxm.html

[Q83] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtmzgrwgjy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtbpgvqzkd.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gtlgjvifkk.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtbdoofjpf.html

[Q85] 数值取整
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhylaojp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gtduwjkplu.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtdcewrdqq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gtvjbhhhmf.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gtbyoibxpb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtxspqmqca.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenjidiqi.icu/Article/details/gtxkxsmlvl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtsnwzfhsn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtwxczgdwf.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtbuuaygpk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gtgryntsmg.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gtsjbclahq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtydlvmgiz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdyvtpjnp.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gtmvkbiyqu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtuefknknz.html

[R01] shebang 与严格模式
来源：http://dali.meibo888.top/Article/details/gtvrczpzhw.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gtadeiisoy.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gtltnsmeho.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gthuleoznq.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gtaxzczvmc.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtgnazhhzp.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gttzokbern.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gtmgpvxlci.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gtaqeimfkt.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gtdqietqis.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtozpjvcfy.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtgmvrvebr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gtvfurhvke.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtjwqvmzdv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvyfaruf.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gtxodkwgmb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtyvgpxysz.html

[R09] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtmkfjuruo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gthiwrffyg.html

[R10] 正则匹配
来源：http://dali.zhengqikj.top/Article/details/gtbkvwskva.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtfspfqoss.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gtetuxumed.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gtqigjszgj.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtqoxulplq.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gtcgegeqms.html

*)     echo "未知命令" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofsewrrl.html

esac
来源：http://dali.aizwys.cn/Article/details/gtfygprvks.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gtvdocykxg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtgjyltvbf.html

[R13] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtqrodpofn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtarigtpsg.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gtflxnudjn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtxrahzbby.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gtazarpvwg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gtrchezefv.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gtludzmbft.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvevzvay.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtjrdqzndr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gtthxqijkp.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gtdqltlweb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gtbkesipin.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gtloxscsit.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gtnzbpbxfx.html

[R20] 关联数组（字典）
来源：http://dali.haohaochexian.top/Article/details/gtqfotfndu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesnrjhav.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdtgtxjp.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gtkdsupvlr.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtzsgqbzfh.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gtepgpyycp.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtkrzusxvc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtshpcryny.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtmmidpxdd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gtaljqhmoo.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gtmmgopvmh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gtaclgwpko.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtrfmbmnsr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtehoijzxf.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtuitwrmdw.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtxhgbflfn.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gteuufqkcp.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gtczccmhtw.html

[R29] 定义函数
来源：http://dali.316326.xyz/Article/details/gtidjqgsmy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gtolmugwjl.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gtuuninljf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtqkyhcicv.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gteumyiuoa.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gtqqpynntq.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gtuyxkfjfh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlxhkicmm.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gtuzbyufle.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gtrauxymmm.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtdbiextcu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtyphgtpkp.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtbcwyxugo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gtijncnmkd.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gtcarfjxaz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtwxabavwk.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gtdmmebygh.html

files=$(ls -1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbqtsfbsq.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gtinlwfqrf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gtfvwbvjjk.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtsgzpkxmi.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gthchhffxy.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gtdqpvxdyv.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gtxbofcqml.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtohfrllos.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtkifuhokd.html

[R42] 输入重定向
来源：http://dali.chenzaomai.com/Article/details/gtlrlxcpmk.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gthnnoqwrz.html

[R43] 按名字查找文件
来源：http://dali.hammf.cn/Article/details/gtcvqotmcy.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gtistxzpil.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gtqbwjbsnu.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdqettke.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gtrmxfzeac.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gtucrlbtos.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gtlkpjfcie.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtjpcxqkan.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gtcbbuegrv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gteaepcgcg.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gtlkwgdwva.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtwrhsvdrr.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gtkbelnnib.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gtmigbedrd.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gteftbrruk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gtlhqwtcuq.html

[R51] 排序去重取前几
来源：http://dali.sweek.top/Article/details/gtfieogjqh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gtdrxpifgs.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gtgpijvono.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtpltpbhbt.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gtzvwfoklr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtpkylapmi.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gtijybouvr.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtwvbqvrfr.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gtbsicamsd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangshuangyany.cn/Article/details/gtispzqmub.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtzkqxdxgl.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gtboemkvvv.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gtuhaxkvki.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gtonymuzxm.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gtkgkrodix.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gtegqwviyo.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtptqxgsan.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gtfymuetuh.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtyrlmhhzj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtkthxqpoj.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtebgkhsgx.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gtzywtuvrh.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gtihqvsicp.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtashnzdnh.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gttjwyovvw.html

free -h;  ps aux | grep nginx
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthakpwhco.html

[R64] 结束进程
来源：http://dali.yueranfly.top/Article/details/gtueysiyfq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtoupbuoae.html

[R65] 查看端口占用
来源：http://dali.yanxiufei.cn/Article/details/gtmsiejlar.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gtcofbfjui.html

[R66] 定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepkndbip.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gtwajdbutw.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gtpwgjqnii.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwiacwgy.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtottoazwb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtlrajagml.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtqaxlnnjw.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gtymctvqiv.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gtezeymniv.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gttdlzbarc.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtyldwjpcc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.316326.xyz/Article/details/gtmbcdboqo.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gtdzoceuhw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtdqpxhzkc.html

[R73] 分割大日志
来源：http://dali.dashuyun.cn/Article/details/gtebdqebpl.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtxzppbwnl.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gthzhoqlkg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gtxstbcysu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtwubeujlq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gtflhlwidc.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gtyrihztei.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtgqqbsmfv.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtxbxxroqh.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gthpghlqdg.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gtpbyisith.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gthvdndqgh.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtllxjtinj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtuylgodsd.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtvsckqyix.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtrohxkjec.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtyftcvbcz.html

S. C / C++ 专题
来源：http://dali.0kj1m.cn/Article/details/gtwdgyeaut.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtiqelsiyv.html

[S01] C：Hello World
来源：http://dali.xziqi.cn/Article/details/gtgprypdnh.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gtqkxqsugp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gtqxeobzoi.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gtaohpyvot.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtaszvuyfi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gtlxwvpbjp.html

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gtemohvbhs.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtbrugwoju.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gtmarvvjca.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtgymrstrx.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtyetmbfiv.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtintfxdae.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gtrjsdaotd.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtbfuicine.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gtybshlpva.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtuadiqogr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gtbttpfxtv.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gtdbulqcun.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gtcpmwhzhx.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gtomjbzznh.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtyxevreet.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtbptffdga.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gttfhsroda.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gtbfrjoblf.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtpnfhucsk.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmijhotrm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yonumen.top/Article/details/gtgzijitqg.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gtqukthjik.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gtbjtwdfcg.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gtjxrnpkht.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gtebrolbmh.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtmnipoysz.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gtffnyjqtq.html

[S16] C：位操作置位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjphlywkw.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gteomrmnmg.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtausgttvv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gtxfovnnuj.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtvszeraru.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtgsbhufeu.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtbpxffmav.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtwwwojaqy.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtoufewrio.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtiecvoinp.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gtennuotxy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtovywihir.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtmzcegmcy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlvssfca.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtvxqcdftm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gtbfpbzhwh.html

[S24] C：获取本地时间
来源：http://dali.cashguo.top/Article/details/gtdeuatgch.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gtjnwwugie.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtfwzghwaa.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gtqnqoornf.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gtwnvadphh.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gtzhfldbdq.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtqjbwmpic.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtzgfddluf.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtlcntadhw.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gtxsyscyyo.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtqtjcduge.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtrnwmwxgr.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuizooomo.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gtsldpsfhd.html

#define X_H
来源：http://dali.wangshuangyany.cn/Article/details/gthfftzoot.html

#endif
来源：http://dali.ywan-chungtsiang.top/Article/details/gttctxxhic.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtypxacjel.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gthduihqsx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gtqmnqimhk.html

[S32] C++：字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtcwxebnmr.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gtqckdjzpc.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gtuptdpvzn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtcrdcrslp.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gtuhxnrrqf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtkwiwdzje.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtkjzksbop.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtzalsvumz.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtpgdabemo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtqonbspnl.html

[S37] C++：set
来源：http://dali.hongshengwenyu.top/Article/details/gtaivwyelh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gtzwxghuae.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gtqxlyjsjm.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtzgsokdub.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gtmhgyodtd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gtzauxmcin.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtjmouyuta.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtwwqhogoo.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtxosjelom.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gogol.net.cn/Article/details/gtruihrqek.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gtvyuznzqh.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gtyjkkwwsg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtgqcfivnw.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gttfywtmmi.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gtvgpvintb.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvzwydef.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gtffndcwes.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gttxezavrd.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtzjaobytw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gtfeolwzqe.html

[S47] C++：结构化绑定遍历
来源：http://dali.daria6918.cn/Article/details/gtlnejdfox.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gtfpswsxva.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtjwbfraoh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtashponyj.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtjrofjnmb.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gtjdwbrmiy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gtyrepfioa.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gtiaikmaey.html


<!-- 参考信息 -->