代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlvkeye.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2ubdyxhmh.html

[Q83] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gt2yybhwtiy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2sypjzelb.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gt2vdaenhbg.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2tpvomogj.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gt2itxbjfdv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gt2cawafzwb.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gt2uuhxftmo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gt2vaipqalh.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gt2mierkinw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gt2qmqbjgyv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gt2uyjpqqrk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gt2axicjoqq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2adzglkgj.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2aqrqqjek.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gt2pawevmnt.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gt2pvumgfja.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gt2oqembmwi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2rtlnsoul.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gt2wevmvnjx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2xvmlketu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgkyjnc.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gt2udnzolly.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gt2xiotvwkp.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gt2ginbjrkf.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gt2dhuaqvrq.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gt2vdncvytt.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gt2izcnjeuh.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gt2elfrtndg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdsffkbs.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gt2hfeeyzqt.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gt2ixusfkxr.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2swjdtxmd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2zrwzhkkw.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gt2dkxjasqu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gt2fyhzieqe.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gt2edgwujbz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xiznsorf.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2otkhqnlg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gt2nymeninu.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2ymoiavvx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gt2qmbxnfmk.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gt2ykqjxwle.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gt2hmsapqkl.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gt2xktjlesa.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gt2fjztetav.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2mkddttrp.html

esac
来源：http://dali.hywenlv.cn/Article/details/gt2bzezezkz.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gt2ksgpduou.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gt2mfopgocl.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gt2lbodnvxk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugfgdimb.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2neqrtbci.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2xcpnogmb.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2vtiicbjj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.iojbl.cn/Article/details/gt2osnalhbh.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gt2qwuxajeo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojihbmaz.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gt2xkftjiaj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gt2llapsdee.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gt2ujcjrfhh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aetrwglw.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gt2oxwrttnl.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrhzwtts.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gt2nshhjdyl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gt2zwqulhkw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpzpggl.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gt2hulypotm.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2nenhgzlc.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gt2ebspiduo.html

[R23] 字符串替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnfdhjyw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gt2qtvuwzjv.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2mwkzkzoz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gt2bjhyrugy.html

[R25] 去后缀 / 去前缀
来源：http://dali.9152youxi.cn/Article/details/gt2aasasdya.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gt2dmjszqid.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wynyjdas.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gt2bsijrlgk.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gt2azwjkiml.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gt2iymstewo.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gt2punoekvm.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gt2gesntpas.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylgiryep.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258888.top/Article/details/gt2xknepfaz.html

[R30] 函数返回状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uujfmiyp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.mhx1999.top/Article/details/gt2addjqjjo.html

[R31] 局部变量
来源：http://dali.yangfankeji.com/Article/details/gt2hgeqlghv.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhgjllcp.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gt2rxaqzdlr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2xdunghgy.html

[R33] 捕获错误并提示行号
来源：http://dali.yanxiufei.cn/Article/details/gt2codvyewp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gt2hdfoomar.html

[R34] 退出时清理
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvqavbdy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gt2nbftozgs.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gt2qqpvzwhr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gt2begxqvuw.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gt2wsquzbra.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gt2uqzijeiv.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gt2htskvylz.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gt2evfzianx.html

[R38] 管道串联
来源：http://dali.nwbrower.top/Article/details/gt2hkzvloqh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gt2tloidbkh.html

[R39] 重定向标准输出与错误
来源：http://dali.zdqjudy.top/Article/details/gt2dmapridm.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gt2faovrjpl.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gt2ydvihwlx.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gt2kwjvqkhn.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2ululyoqx.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gt2ifzqfryz.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gt2udbrxjkl.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gt2hrlvxozy.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gt2qxltghtm.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gt2lzvcyxto.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwfecjtl.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gt2wzagatwt.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gt2vfhjjhie.html

find . -name "*.tmp" -delete
来源：http://dali.nanxinkj.top/Article/details/gt2rgzrdazu.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gt2qajmzkxj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gt2pdxrqstc.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gt2xuhgkagd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gt2jtxfyuay.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gt2irosolyh.html

awk '{print $1, $3}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2fucsiwaq.html

[R49] awk 带条件
来源：http://dali.cdnleiting.top/Article/details/gt2gcdsbchm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gt2vqdrenbf.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwjtkedd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2cgpwaamy.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gt2zunqecjo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxseazkh.html

[R52] 统计行数
来源：http://dali.gotoacloud.top/Article/details/gt2wsjozfad.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2ljjmlflq.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gt2merbkgik.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gt2auazbvif.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gt2gmsplojh.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gt2jolzfpmi.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gt2cpenzdqt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgbivfcc.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gt2hoklscwa.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2zlmarupg.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gt2llsiqgbo.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gt2nbwdvuqg.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gt2umajjiht.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daxiang520.top/Article/details/gt2rgjzkvuj.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnbznjhw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gt2rthchgij.html

[R60] 只看 HTTP 状态码
来源：http://dali.yongpay.top/Article/details/gt2scxuyetk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gt2ykvboklv.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2fozdmkon.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gt2eujuzfeb.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2yeukpgtl.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gt2mnyaxjkf.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovqjmezc.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gt2qewrjtbp.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gt2qrvqnlxe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gt2uficorhq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2deircikt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gt2pspdylpl.html

[R66] 定时任务
来源：http://dali.fengsongda.top/Article/details/gt2qzppgdtz.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2zaynssya.html

[R67] 生成随机十六进制串
来源：http://dali.sweek.top/Article/details/gt2qncyiwyz.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gt2vnjvrqgi.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gt2tbwteoaq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2wzgdkztu.html

[R69] 生成随机密码
来源：http://dali.xziqi.cn/Article/details/gt2nxowjceh.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdahtehg.html

[R70] 时间戳与互转
来源：http://dali.cdnleiting.top/Article/details/gt2jlshpkph.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gt2nodhypvj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zalwmghj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gt2cwkptrom.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gt2tjpffbzx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2okmazury.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gt2lbmpbgpi.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gt2akonitmb.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gt2remncyma.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gt2pmfanclv.html

[R75] 导出环境变量
来源：http://dali.yj20258.top/Article/details/gt2fjtrkhai.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gt2hhzpdkzk.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gt2uzvnfwxc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gt2xgdiapss.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gt2rihtsrad.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gt2ptxlrbll.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gt2npkjvhxo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gt2zselfbpb.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gt2agralbhb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gt2iinzynqp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gt2ynvuuyar.html

time ./run.sh
来源：http://dali.jlsjyb.cn/Article/details/gt2bmekawlu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2zyvxmalf.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gt2ujtduutj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2lwdudttd.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2rarwollu.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gt2tuklqzxd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fdtdqqmk.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gt2orexrzwz.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gt2xhjqmkqf.html

[S03] C：读入整数
来源：http://dali.hammf.cn/Article/details/gt2vbkturay.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gt2aozurxjc.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gt2gtxgjtku.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gt2mvbtzadk.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2czzhmvhd.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gt2tsysnocp.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2bmogglaa.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gt2qubsnpne.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gt2dpaojwws.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gt2putkwdrr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gt2ufliilll.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rpaosmrj.html

[S09] C：结构体定义与初始化
来源：http://dali.ppjwa.cn/Article/details/gt2dachnmbg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gt2kjsnbibg.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gt2fwulnqpp.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ummhokop.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2ilcqytya.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahbyuijx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gt2ioqzxoef.html

fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gt2kyizkoks.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gt2qscnhprd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gt2hvyquspi.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gt2oagbobec.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgztmazc.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gt2hyflgqtx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gt2tcmvjuhk.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gt2nfrvtftp.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gt2bbrpsrps.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2daqqjnxe.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gt2lcpltart.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2egpvhdfj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gt2esqrqpku.html

[S18] C：命令行参数
来源：http://dali.dianchejie.cn/Article/details/gt2feaicuml.html

int main(int argc, char **argv)
来源：http://dali.yongpay.top/Article/details/gt2vmzhpruz.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gt2anbepzcu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gt2sypjuvar.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gt2pqsxuajv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gt2vgvszaop.html

[S21] C：字符类别判断
来源：http://dali.ivvv.top/Article/details/gt2oznkbwhb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gt2banelbsv.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gt2dsbwgbut.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gt2onpgqctf.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gt2meixtdyp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gt2wkfvekjx.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gt2srfmqgoe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gt2btxqaazq.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2nofjuogj.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gt2wbjhbaoc.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gt2fvqeuuze.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gt2kssvqtwc.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gt2twqazcqg.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2fssplwza.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gt2qdqrkpgr.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gt2uiyvnolf.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gt2wnzglekc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.vqdsnc.cn/Article/details/gt2ggkxrhci.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gt2fhlrwlva.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gt2wrfncjka.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gt2bbxzhoxk.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gt2rulgzgzb.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2vvomettv.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gt2rlmoavat.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gt2pxjjfvcm.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2zwanbvnw.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gt2lvdcimxw.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gt2clwbhzqu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gt2suzwoltl.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhjwzvyi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gt2jyeinurm.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gt2tzfbkcqu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gt2ynykyzle.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gt2ecgmlaxu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2lkzuihhc.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gt2uhdzsuef.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujolauuu.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gt2ksrxdgop.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2ferywync.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gt2dvnqmwsu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyxaxhip.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2jukjpuag.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gt2jezomoez.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2xwisxpfj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqcpjpqw.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gt2mqgrosus.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gt2zbmcinln.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gt2kllkmbrl.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gt2gdbzntxm.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gt2mskqzabt.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gt2viygrrqm.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gt2iiwdpihb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2epubzccf.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gt2sdevracl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gt2zptyqzhw.html

[S47] C++：结构化绑定遍历
来源：http://dali.dianchejie.cn/Article/details/gt2upxoinuh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zshzafad.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggeguaum.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gt2eqxretbd.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gt2jistuypw.html

[S49] C++：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2tyzdmvhy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gt2ahpvppht.html

[S50] C++：格式化数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2odnzvpdc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2oqozokby.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gt2azkikeko.html

static_cast<double>(a) / b
来源：http://dali.tanke756.top/Article/details/gt2ndcqujzy.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gt2oswfcuqe.html


<!-- 参考信息 -->