代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gt2ekjnzkem.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2gtejxull.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2wgqpwwog.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2elinudub.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gt2eihypotw.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2qxqlticz.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gt2rqqhmytl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gt2skcvhjbz.html

[Q86] 读取 JSON 字段
来源：http://dali.hywenlv.cn/Article/details/gt2fuontqea.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj202588.top/Article/details/gt2hwgsujcv.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gt2wezvgfzo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.birdmap.top/Article/details/gt2vhephfxq.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gt2htgplima.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulowqefz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vleszgpq.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gt2xcvkgsts.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gt2yvnurdlq.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gt2gdsnbnsh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gt2ojulnrkf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2iwugswjn.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gt2efxttmpg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2fnvtfzwd.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygkwnkyp.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gt2hpqshmgh.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gt2qchgumll.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gt2oluelufy.html

name="Tom"; echo "$name"
来源：http://dali.cdnleiting.top/Article/details/gt2pffahrgs.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gt2bfhiqnsb.html

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gt2mzfxjeet.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gt2kmuzzaay.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qairkkly.html

[R05] 参数默认值
来源：http://dali.andypj.xyz/Article/details/gt2gusrquqg.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gt2sppkzqxo.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2cqddjcxm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2uobrcqep.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gt2zolvbfqw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlpntdwe.html

[R08] 数值比较
来源：http://dali.cdnleiting.top/Article/details/gt2ugvvxier.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zycfv.cn/Article/details/gt2usqtqrwx.html

[R09] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gt2ynupyoob.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gt2mrziyjcm.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gt2kjozmmgy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2nwrlqpye.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gt2cnkyfaar.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gt2tglophqf.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2vbphqwcu.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gt2tcqesxum.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gt2rjcgkstl.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdfdibkv.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2pudbnive.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gt2oxvucxgw.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gt2vvjqxzra.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzpafrjq.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gt2mtsoxxxv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujheujze.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2dperxhmt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shuidangran.top/Article/details/gt2szmmzupy.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gt2uhvemnrv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gt2tompciit.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gt2zjvimetf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gt2azpykrgb.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gt2jlrnwpgn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gt2vbnrtyqe.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2ratlfflb.html

echo "${#arr[@]}"
来源：http://dali.snrcjt.cn/Article/details/gt2kiutnvgg.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gt2wyisvqwg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gt2ctycyivn.html

[R21] 字符串长度
来源：http://dali.9152youxi.cn/Article/details/gt2cszylcpp.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gt2biozfrvn.html

[R22] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2iumjqajh.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gt2loyulrmq.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2oysygzrj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gt2tktngxkc.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gt2ewolckrs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gt2onkggyoh.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gt2ejuogial.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gt2eiuyryjk.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2tprxlrnu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyuppawm.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gt2tkqofmyr.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjsujjpx.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gt2erhgueet.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gt2idldlnkx.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gt2olqhgsic.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gt2tqbydeqr.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gt2koliiveb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gt2bdmtfbge.html

[R31] 局部变量
来源：http://dali.chenzaomai.com/Article/details/gt2vmtzwudq.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ixitsmwk.html

[R32] 参数个数校验
来源：http://dali.yongpay.top/Article/details/gt2tfxfjmpq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2rakmsniq.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2wicujkln.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gt2vefepyjk.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gt2aupcctid.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2ddpilzht.html

[R35] 后台执行并等待
来源：http://dali.0kj1m.cn/Article/details/gt2aseaewzm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gt2hlgkeuca.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gt2pcsxxnym.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvufhrbu.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gt2ivaqupzu.html

files=$(ls -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2lizvlubg.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gt2qxguqyam.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gt2sxncqrsi.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igyxtcjc.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2gvvgseij.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asmengah.html

echo "log" >> out.log
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjqvydac.html

[R41] 丢弃输出
来源：http://dali.cdnleiting.top/Article/details/gt2jijijvcs.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gt2fcslsxmt.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gt2akkxqsua.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddfxmyqp.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gt2svorpblg.html

find . -name "*.log" -type f
来源：http://dali.daxiang520.top/Article/details/gt2vkmqhyst.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylsuemam.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gt2siuasexj.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gt2ehraasrr.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gt2pbqhifvr.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gt2nsrfgmdd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gt2rjvcgaos.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gt2mbnpmqxu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2vmeawvjm.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gt2dcirjxvt.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2btpdczot.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gt2vtydrnwd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gt2bysszrxz.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gt2zgvtouvj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2kbfquxor.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxyzlwjc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.iojbl.cn/Article/details/gt2qruloody.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2sirboxpl.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjkotlnm.html

[R53] 查看文件头与实时尾
来源：http://dali.andypj.xyz/Article/details/gt2lsdytpdo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fzhhl.top/Article/details/gt2ipijglta.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfwmfmnh.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gt2wypkmsdi.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnykkxid.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gt2cnmrgspx.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gt2oddyvpwe.html

scp file user@host:/path/
来源：http://dali.aibaodan.cn/Article/details/gt2duwnzygk.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gt2rejuxjej.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gt2roauvtjx.html

[R58] 下载文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyduiuqc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2iylbpcnj.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gt2hqlrozte.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gt2exapeqty.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gt2jjxxayrl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gt2kyjalizp.html

[R61] 磁盘占用
来源：http://dali.jlsjyb.cn/Article/details/gt2gephfrip.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gt2lzrvlkjq.html

[R62] 找最占空间的文件
来源：http://dali.gogol.net.cn/Article/details/gt2cbvsntwf.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gt2mtktknlu.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gt2bckjgphu.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gt2phclcswx.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gt2ndmtltwm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gt2ltzsguor.html

[R65] 查看端口占用
来源：http://dali.chenlongwang.top/Article/details/gt2ygbmgjjm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gt2fbqrqodb.html

[R66] 定时任务
来源：http://dali.hywenlv.cn/Article/details/gt2cszzeppt.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gt2jjpsxfxn.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gt2qmdosrsd.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gt2bbavlsob.html

[R68] 计算文件校验值
来源：http://dali.andypj.xyz/Article/details/gt2gtpsqmcv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2ghtslnwe.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gt2rneqdtfd.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gt2hwcjyyet.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gt2fpujqrua.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gt2tiqguhez.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2sgdrwesu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gt2dajkasft.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gt2hjrcwmwh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gt2swafadwp.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gt2araftnpl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqmdink.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbfirzfr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gt2neuvugzb.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2wahyuhtn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocmkantg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaivozu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gt2vurtpgij.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnysvryf.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gt2fwcffohx.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfmrwrtv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gt2famcrqzn.html

[R79] 解析命令行选项
来源：http://dali.aizwys.cn/Article/details/gt2dxtkjdgb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gt2nitkldms.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gt2wpqdutah.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gt2iymgttht.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2yqmrhsib.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gt2eeuaeolv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2gnaablyk.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2bzmnnxiz.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gt2mgnljglj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gt2ajqetkbc.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gt2dafymvei.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gt2fyapblhj.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gt2qvakcqqh.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gt2kghyyjoj.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gt2ggzyolhv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gt2trhlgjav.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2xyfsvrcq.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gt2khfcymbx.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2hapmlqtc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcpstgx.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gt2zwpsyatb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gt2frzvfnnt.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gt2cyyovyjh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gt2wsfeatrb.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gt2nznezvdm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2tptqlrfx.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gt2rhavdruw.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjfijpuv.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2owibhtci.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtlqpmfj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2dygpsmyl.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2xyedatbo.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gt2ywmlynlp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gt2sbjwpvpz.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gt2jdkedsoj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oimbaruv.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gt2arcwsatn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gt2fmgzrjby.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gt2umpethbw.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wywgungc.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gt2jxfpiern.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gt2vahhepbi.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2ellwozfx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gt2zyrszjpy.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gt2iilrcrsa.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gt2mimxnfhm.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gt2btxnmurj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2efdorekm.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gt2vzbusxev.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2ixdostyg.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gt2nnwpvwtk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gt2fcizsoll.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gt2zrtpzqvd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gt2ddpzmbsz.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gt2yhytozgd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smmufizt.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gt2ocoybvvc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gt2kkqkudty.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2mvckmuhu.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gt2dpiexnok.html

[S26] C：内存清零
来源：http://dali.gzhubu.top/Article/details/gt2qwyxfeod.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gt2neywveud.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gt2byyqjsgi.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2rrvanevo.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2qyldtkem.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2iemoqfod.html

[S29] C：变参函数
来源：http://dali.guannengcc.top/Article/details/gt2pcfvtxba.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gt2fnyqnltg.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gt2lmetycdq.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gt2opcevsha.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gt2whrgutix.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gt2fxcscmmi.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2qupdasga.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gt2dctviwze.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gt2okjppocq.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gt2jnofqpxf.html

std::string s = "hi";  s += "!";
来源：http://dali.aibaodan.cn/Article/details/gt2ozlkhqbd.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gt2rhykeujv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gt2aaylecaa.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gt2czcpnrbe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gt2fbcgyzxx.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gt2maqfnqiw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2qalxwxfc.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gt2dkxobbvy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2twybrijj.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gt2xlepqoup.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2lidjziow.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gt2pqxigdwz.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gt2pmedexgz.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gt2lmczxcrv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.redwolf501.top/Article/details/gt2cykiuowz.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gt2vrmkaqqe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohtojdam.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2ovvhhfyv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gt2pquzaxnr.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gt2ifimbrzh.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gt2tglmqqds.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gt2zcrwmfkz.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gt2diibmryb.html

[S44] C++：引用传参
来源：http://dali.yangfankeji.com/Article/details/gt2zfmhintw.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gt2nezgjoni.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gt2srctfdlo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gt2uglqfjsk.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gt2mvcoafuk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2giuludzy.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxinkj.top/Article/details/gt2kzemgzmc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gt2scwzuzdk.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjrlycwc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gt2ngambale.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gt2edmdafpn.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gt2uldlvvqv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gt2jambsurl.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gt2jdsnkmzo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atgjyzbw.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gt2gvigxegv.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gt2zydyhivf.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gt2erpvcwvu.html


<!-- 参考信息 -->