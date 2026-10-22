代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gt2vzahmaax.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2gwmjbyuy.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2yeiptxom.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2jvoxvzar.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgzkgrkx.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdbxfeda.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gt2zccydjrp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gt2squhawol.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gt2aifrncal.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gt2pwmqalox.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gt2repaqvek.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kovicnry.html

[Q88] 行转列（条件聚合）
来源：http://dali.hfpthk.cn/Article/details/gt2psrdrjss.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.redwolf501.top/Article/details/gt2gykzmpkz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2wvgjbwpe.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2tfqxmfuz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gt2tzzxcypx.html

[Q90] 生成序号列
来源：http://dali.smart0.xyz/Article/details/gt2cexsjxsh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gt2ziqkbawu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptngrblv.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyxbspgd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ltxagbew.html

[R01] shebang 与严格模式
来源：http://dali.hfpthk.cn/Article/details/gt2ciuxyfwa.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqwvgjtm.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gt2jildcycz.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msfhgndc.html

name="Tom"; echo "$name"
来源：http://dali.0kj1m.cn/Article/details/gt2kazfadzq.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gt2wwdfujwf.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gt2nbvwmlch.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gt2rdhjuiqa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gt2xdkvxxmo.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gt2jjynogzh.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gt2moarkpcg.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gt2feangbpu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gt2lrvbegyv.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gt2iwvaowtp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gt2ahvekvcs.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gt2tserenld.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2asapdjih.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ullsxxik.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gt2gsrypjvd.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otiexugx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gt2ngnixywb.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gt2wbkukych.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gt2aczeyqtu.html

start) echo "启动" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2jzqmknqp.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2dvngshpn.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gt2cnwqfshw.html

esac
来源：http://dali.redwolf501.top/Article/details/gt2ztvuiuyj.html

[R12] for 遍历文件
来源：http://dali.shuidangran.top/Article/details/gt2pnndouiz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gt2skfkczdx.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gt2irmacoiw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2cxnshuwu.html

[R14] C 风格 for
来源：http://dali.jiagoushi.top/Article/details/gt2rswbklhj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gt2azlynenh.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2lxvdxwqy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gt2adgfidru.html

[R16] until 等待条件
来源：http://dali.cucudq.cn/Article/details/gt2ogupsuun.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2iolnzheb.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gt2ocfhnrdt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gt2htjuhbfa.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gt2ibtjmhkt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gt2gscmgovn.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gt2zsmfxtdd.html

echo "${#arr[@]}"
来源：http://dali.jqgfzy.top/Article/details/gt2skjbiqfh.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gt2jgzihqnj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gt2jcmhonve.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gt2usmsrdcc.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gt2vvpnhcwj.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2efjwtjul.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plggmzei.html

[R23] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gt2zlokbisj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgigrtfv.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gt2imbfjopr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmhmqcwd.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gt2umhmcgeg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.andypj.xyz/Article/details/gt2zdeqbcex.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqixvgxy.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gt2ryshziac.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gt2klrfdmni.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gt2pynnvmdj.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gt2ybieuzrm.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gt2qzzmfegr.html

[R29] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gt2ivoiejlz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gt2naoecclx.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2lmnusurd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hywenlv.cn/Article/details/gt2yoxjyykz.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gt2yeptvfzc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2yguhwmtl.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtdarvqi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yonumen.top/Article/details/gt2dwvbpcxc.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gt2wrgmtedf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gt2bqazfmgg.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gt2vqquvygv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gt2adyijfzw.html

[R35] 后台执行并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcycahqi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gt2wsjqyait.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gt2aohalqsv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sykftwwz.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gt2whmodaei.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gt2uhsjlude.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxhwfauq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gt2trsamvvu.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gt2sqohwwwn.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gt2ceqtddjb.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gt2fukpkbvl.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqlaxvww.html

[R41] 丢弃输出
来源：http://dali.jyoumei.cn/Article/details/gt2hwdafnjw.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2wzqenrrh.html

[R42] 输入重定向
来源：http://dali.shuidangran.top/Article/details/gt2csppwvae.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gt2mdidwurq.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gt2mnjjgafw.html

find . -name "*.log" -type f
来源：http://dali.zycfv.cn/Article/details/gt2sdimxnkq.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gt2sdtrtsot.html

find . -mtime -7 -type f
来源：http://dali.yonumen.top/Article/details/gt2avclymxe.html

[R45] 批量删除
来源：http://dali.yuanzhike.top/Article/details/gt2kqegogga.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gt2ggkivqan.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gt2vidwwucq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gt2kiaonvaz.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gt2puhcront.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gt2qwciaovm.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gt2syonopky.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2jcqnjgjf.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gt2jemhnamc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gt2nwbciosh.html

[R50] awk 求和
来源：http://dali.yuanzhike.top/Article/details/gt2fyzioxkx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2ufkabqsr.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gt2qdrpfgip.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gt2ndhqvdbx.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gt2wndxhxzv.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awumpwmg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tekvsjds.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gt2ygvbrgfi.html

[R54] 比较两个文件
来源：http://dali.zdqjudy.top/Article/details/gt2cstftaoq.html

diff a.txt b.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhxeppwf.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gt2vjcooelw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gt2vcrfbdac.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gt2voqjjyli.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gt2nisohhyp.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gt2mnpmjaro.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gt2dwskmruf.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2cutwcatg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gt2eccomruw.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gt2eicgdlzo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gt2anmcifvg.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlyyykyw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gt2poehamvq.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gt2subjgrvy.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gt2esgknnoj.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gt2mshqitya.html

du -ah . | sort -rh | head -10
来源：http://dali.ydzc1.top/Article/details/gt2rclddeww.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gt2sijjvtka.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvwzphnu.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gt2pbfyaviy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gt2ahvufosu.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gt2nuebzaaf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gt2yrttwacf.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gt2sqoqplqk.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gt2oprhiujk.html

[R67] 生成随机十六进制串
来源：http://dali.ivvv.top/Article/details/gt2wyhnukat.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gt2vlnibzlk.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gt2dqnoiyjv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2dwmcgakq.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gt2blotiedr.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gt2ujbvqyhb.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gt2fzgtfhdl.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gt2eqaknztu.html

[R71] 日期格式化
来源：http://dali.yonumen.top/Article/details/gt2rgoohqqm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gt2mkrnzmfu.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsrdjssa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gt2iuwqtwum.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gt2nboetvkv.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gt2utjvmlxy.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igkkefde.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gt2fsouoxha.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gt2rjkxwxqy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gt2urpszmbw.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kapltldp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gt2tpdpxhjt.html

[R77] 读取用户输入
来源：http://dali.jlsjyb.cn/Article/details/gt2vyytasbz.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gt2fzsqcixk.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gt2yijpdhhy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gt2rumaddby.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gt2ynjyxpgj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gt2zeocysvq.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gt2hrznoegv.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gt2aplcudmk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2rcbiolwp.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inuksgok.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdxjxxvh.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2uwzbbwbr.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gt2hryjuhlw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gt2nvyyjnnl.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2fbsutebv.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gt2xejjslvy.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gt2xzlfftmq.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phfoeanw.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gt2lxhyconu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2cgcwalrq.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gt2tfwlimcp.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gt2moeggpps.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2tkxvvxgm.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gt2usehuwne.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gt2otajbckf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gt2mklxmiuj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gt2bkyqmvtj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnqzz.top/Article/details/gt2bdvdnjwf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnmaucy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cdnleiting.top/Article/details/gt2tmuldypo.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gt2shvawqyb.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gt2itfuqzyd.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2jpvoirob.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gt2drizyrnv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avgdxhro.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2fblotksp.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2kchyykdw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gt2fgpaxnad.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gt2cdbeoayc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gt2hjjkzxol.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gt2supwtrxe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gt2plvmxnsc.html

[S15] C：类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnkltmum.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gt2vfztdmgt.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gt2jbnkhkvv.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gt2dhvbhzlp.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2jsunvqzy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gt2dszfbeir.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gt2vtvrjijh.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gt2ieumrjns.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gt2khgholnr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2ewxblqyh.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gt2fmfazdhi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gt2dluqkvov.html

[S21] C：字符类别判断
来源：http://dali.jlsjyb.cn/Article/details/gt2tjobxqtf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gt2kyuxdrvj.html

[S22] C：字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gt2lrxspmrs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gt2updoirxh.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gt2gsyywbow.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gt2tidklgmq.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gt2upnaokgv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gt2rwnxmxci.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2pquifvxi.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gt2drtlfvgf.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzvfllwo.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gt2zidvdukr.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gt2ebonasdw.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2uhvgqpos.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gt2gbnmdbbb.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gt2qesnzugk.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gt2fhyykhag.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gt2yjrqrlbz.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gt2sxqrdlbb.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gt2fwzanwzb.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gt2fzwwmwaw.html

#endif
来源：http://dali.c1oappe.top/Article/details/gt2qrbfhmwy.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2xiaxwttb.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gt2obymicqq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bmyyxnfg.html

[S32] C++：字符串
来源：http://dali.nanxinkj.top/Article/details/gt2gwaiwhmj.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwcxfgdl.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gt2tkqmolcy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gt2gzjkgqfm.html

[S34] C++：遍历 vector
来源：http://dali.nanxinkj.top/Article/details/gt2ksolyhvt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gt2yohvynbm.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gt2dyjizzai.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2csplhbbz.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gt2hilhwpiq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2ihqalfsl.html

[S37] C++：set
来源：http://dali.cdnleiting.top/Article/details/gt2swszqvve.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gt2ujuiqsbl.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gt2egzfjkwa.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2cqshnulz.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gt2wybhbjim.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hammf.cn/Article/details/gt2chmcitrn.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gt2rqpgeckk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jiagoushi.top/Article/details/gt2ukgvktto.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2fvwvfriy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gt2ywhstflg.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gt2gzrnrxml.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gt2lcoxnnab.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gt2uvkcaoyp.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gt2vqtslzgu.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gt2ibgwield.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gt2izktuxtn.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gt2wlrckayg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gt2vcrxngll.html

[S46] C++：函数模板
来源：http://dali.dashuyun.cn/Article/details/gt2wpbbygxs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gt2ielxmdda.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gt2hxbxcnff.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gt2mwesxljz.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2xaftnzel.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.svipenyu.cn/Article/details/gt2uubkdeeb.html

while (std::getline(in, line)) { }
来源：http://dali.xinyue.icu/Article/details/gt2pglcmztd.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2benobime.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gt2lmsefwgn.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gt2bjsgzjxu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qiazjasd.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gt2dfxaemkn.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gt2ogvbjivb.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxeaakyl.html


<!-- 参考信息 -->