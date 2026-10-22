代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gt2qglgqoib.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2jtwdvtas.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pteyaeoc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2sotnyeay.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gt2euhsvupm.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2dwybpwad.html

[Q85] 数值取整
来源：http://dali.hfpthk.cn/Article/details/gt2hvcbxgrq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gt2wrdlayvr.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwwupcnt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gt2kyqgsbfc.html

[Q87] JSON 字段做条件
来源：http://dali.dashuyun.cn/Article/details/gt2plhnvero.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gt2cmzuieak.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gt2jkxvebfb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gt2ahfcdxwc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2itgzpaxy.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gt2fbgtqcvv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gt2cprfpeta.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gt2hvakxnmt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjzyspgp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2xdkprvrk.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gt2wfeylmmy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2xlkdnyvq.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgrgxtvp.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gt2vzisaaoa.html

set -euo pipefail
来源：http://dali.jinqigfzy.top/Article/details/gt2nijfcjeh.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gt2hmpfoygs.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gt2mytsivrc.html

[R03] 只读变量
来源：http://dali.kuanghao11.cn/Article/details/gt2ujwbryjh.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnkczhym.html

[R04] 位置参数
来源：http://dali.kuanghao11.cn/Article/details/gt2wmyheizx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sxryk.cn/Article/details/gt2bbfszmaw.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gt2bfcubkbn.html

name="${1:-default}"
来源：http://dali.sysykeji.top/Article/details/gt2cymgwmwh.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gt2yqxcojud.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2wzbyxclj.html

[R07] if 判断文件
来源：http://dali.hfpthk.cn/Article/details/gt2djpobgkt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2ilgfmqec.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gt2kasugkyq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258.top/Article/details/gt2jgpsspxe.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2cxgeikqa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2ykownkse.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gt2fszhocnz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gt2fmltgmqp.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gt2fgykbixd.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gt2izvxjmxf.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gt2kypkfdua.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2losmkeyk.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2xwaywqal.html

esac
来源：http://dali.hysaishi.cn/Article/details/gt2exubdahn.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gt2qzeqruom.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nwbrower.top/Article/details/gt2hwgmdoby.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gt2gwbzxqdk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pgigegoq.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gt2tjopvvej.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdwuxtjh.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2lqkqvoua.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258.top/Article/details/gt2mncvapat.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwirqemr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2scokoonr.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gt2unyrauuw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gt2rwqwmdeo.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gt2uslpsswv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxzgqjim.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gt2vrpartrn.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gt2uyvdhfsc.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gt2kqsswjtx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2qljelnsl.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbhcbkgw.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gt2ukhxclbs.html

[R22] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gt2udcotcoj.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gt2dpwxjzja.html

[R23] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gt2ehjgcgdo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sxryk.cn/Article/details/gt2lgitjmuh.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gt2kzfvqzvk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gt2uaihlenh.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gt2ganleayt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gt2uigwqcnk.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gt2wivvqbpj.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gt2yohbiujb.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gt2iukqrnhr.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gt2mvecmdip.html

[R28] 浮点运算
来源：http://dali.jqgufenzy.top/Article/details/gt2ysitlran.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gt2ollwvckj.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfbvuiuy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gt2tykysiua.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gt2mhaezzjw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guowangkeji.top/Article/details/gt2ofiusrlw.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gt2yakabrem.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gt2wfcqnsek.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gt2gxskbyho.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gt2smoxrixa.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gt2jaslsgcr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gt2lxigwjvh.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gt2sqenkaok.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2muzstuiz.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gt2ihxxqawp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gt2ppqzqlkm.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gt2wsvaypme.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gaibcjek.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmfxbjta.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gt2jrunftbs.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gt2ihtfmckh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cashguo.top/Article/details/gt2rqtorlks.html

[R39] 重定向标准输出与错误
来源：http://dali.xuanzx.com/Article/details/gt2bsrqvaee.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2lynoztdl.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gt2dabivxwf.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gt2plnzgdrn.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqluoxfu.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbtwoegv.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gt2qjmsklnr.html

wc -l < a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2ppexufwm.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gt2dyzpzbwj.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gt2xcqilvzq.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gt2tfvkxvhf.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gt2sckzcvrs.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gt2guogggvk.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gt2likhlonk.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gt2uqplglyh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gt2yxemaqaq.html

[R47] sed 单行替换
来源：http://dali.fengsongda.top/Article/details/gt2hmqhelij.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2gvqdytou.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2polyzesn.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2bgqaxszx.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gt2vyxtefjl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cndaugoh.html

[R50] awk 求和
来源：http://dali.mhx1999.top/Article/details/gt2oqzsxhcm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yonumen.top/Article/details/gt2vtolxgab.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gt2terpiuar.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gt2ebynxxxl.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gt2qsrrygxh.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gt2cfpmdgmy.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gt2xxvitgri.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gt2tdnnyklg.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2wsoqhsis.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gt2flmgsjoq.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gt2tuiwbbnz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gt2jefgnqjj.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gt2kvwoynpe.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gt2fntdhagw.html

[R57] 远程执行命令
来源：http://dali.hfpthk.cn/Article/details/gt2qbbqxbzs.html

ssh user@host 'uptime'
来源：http://dali.zycfv.cn/Article/details/gt2mlkpdsdo.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gt2culgftfs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gt2utwfwryy.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2ksqwnfen.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.0kj1m.cn/Article/details/gt2umhwooub.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2gxrzdtex.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gt2idlgourz.html

[R61] 磁盘占用
来源：http://dali.sxryk.cn/Article/details/gt2qmenklqa.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gt2yhsserbz.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gt2eshblvkh.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gt2zuwkgogt.html

[R63] 内存与进程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2foiiiasi.html

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gt2xrnlesax.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtppipmu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gt2twsyhoqf.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gt2dybsmecr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenzaomai.com/Article/details/gt2tkqmwsgw.html

[R66] 定时任务
来源：http://dali.fzhhl.top/Article/details/gt2flolpogf.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gt2ymgnqnen.html

[R67] 生成随机十六进制串
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfdmvfao.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gt2dkdxvhfd.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gt2dudxjitd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dinxjtmi.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gt2ltjprydv.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ngnxrevp.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gt2bfvphlhm.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gt2xiixypoh.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gt2gaxvlbnv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gt2oaujmvzj.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gt2zouclsli.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2jotisqnx.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gt2bbvrwncm.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpfezfnb.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gt2ijzzmzkm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gt2gzlpacxd.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2hdfckdyq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gt2zrfifdvt.html

[R76] 使用临时文件
来源：http://dali.cheryme.top/Article/details/gt2fbrrvgkx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gt2hgepmncj.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gt2nwipfyfb.html

read -rp "请输入: " ans
来源：http://dali.yuxming.cn/Article/details/gt2ifremozj.html

[R78] 交互式菜单
来源：http://dali.yj202588.top/Article/details/gt2rgsfbyaq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gt2htiwhagt.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gt2uhqenbdq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gt2xoaxeopr.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gt2fjxxaqmt.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gt2wewozdvu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2iplfskng.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gt2dhkhhyii.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2bamjzpwr.html

[S01] C：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svoymdpx.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gt2nufsqsia.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gt2liapeuqw.html

[S02] C：变量与格式化输出
来源：http://dali.yuanzhike.top/Article/details/gt2jsrrqolg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gt2liqvbpyj.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gt2axchpgqe.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gt2rjheiivv.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gt2tjihajal.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmnrbnn.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvylihhx.html

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxpuqtpc.html

[S06] C：字符串比较
来源：http://dali.sweek.top/Article/details/gt2nmahblaw.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gt2svdxfnmc.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gt2bwequwtz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxrlzrmr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gt2qcppkvvf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gt2rckuduuf.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gt2eknstoki.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gt2plvkkwed.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gt2ccggklmn.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gt2rjynkguv.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2pvxzhrcq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzlqkqyk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgvywkgl.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2ixwyfzja.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2kgbavbxx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2tsdpfmrn.html

[S13] C：宏定义
来源：http://dali.hnqzz.top/Article/details/gt2cuixuyum.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gt2yntusbtq.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gt2vytcvygx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gt2dgimcgfb.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gt2kwviqwlw.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gt2pikzhbuq.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gt2wzpdabvl.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2eknxowuv.html

[S17] C：安全拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2rivchpum.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gt2zavmetdz.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2sfbthcjq.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gt2xsljgmky.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gt2ohdvpely.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2lkapqgtm.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gt2mitpmdca.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gt2wovlzees.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gt2wuufqfce.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xinyue.icu/Article/details/gt2wkzwbssc.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2uygenxnl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gt2xqnomxlq.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gt2xijweuur.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gt2tonjkeyq.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gt2qwynalas.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gt2zcawvkrk.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gt2enzqudqi.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dnotzctf.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gt2vknxzwnf.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gt2ofycfiqm.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrueqwlq.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2xgrdqzyn.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbldgxak.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gt2ykeizuub.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gt2vygrcrao.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ivvv.top/Article/details/gt2rypevcfz.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gt2qunpewrk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lemalsuj.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gt2lhfvksvz.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gt2tiftmtfr.html

[S31] C++：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2crxxisrf.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdgoyihd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gt2xulrwmhr.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pssofufv.html

std::string s = "hi";  s += "!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2actqquox.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gt2lasnmlgh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2xaqifxcd.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gt2qmmyhbmg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwczzexi.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gt2etdelbyu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2odohcxrl.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gt2jjbedrwn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2lwewypjp.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gt2smhytqtq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gt2ueppxjou.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gt2wfttwruy.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gt2yqmuzcku.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gt2qbphnwws.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gt2peyuofyw.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gt2bxbayfqx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gt2lqkfdyyr.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gt2zwjfbuth.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gt2orplweac.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gt2oaczqwtc.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtqdwlvr.html

[S43] C++：智能指针
来源：http://dali.hammf.cn/Article/details/gt2ybmfyubs.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2vlclowhx.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gt2modkromb.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlwalsjp.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gt2falcjkth.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gt2jqelblyv.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdhstdbq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cucudq.cn/Article/details/gt2cnooucou.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gt2roqjnrtw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gt2mbfgevxs.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2mcsrrrlt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gt2lpaaoclh.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qikyixue.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gt2smngyrvq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gt2jipjctlr.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gt2xudndgjc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2yoiuhwqn.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gt2edmxabll.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gt2zrtgjozh.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2namgpnkm.html


<!-- 参考信息 -->